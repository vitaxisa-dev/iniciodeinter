<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Recetario Internacional</title>
<style>
/* VARIABLES DE COLOR */
:root {
    --morado-oscuro: #6c3483;
    --morado-claro: #9b59b6;
    --gris-claro: #f2f2f2;
    --gris-oscuro: #333333;
    --blanco: #ffffff;
}

/* ESTILOS GENERALES */
body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: var(--gris-claro);
    color: var(--gris-oscuro);
}

a {
    text-decoration: none;
    color: inherit;
}

/* HEADER */
header {
    background: linear-gradient(90deg, var(--morado-oscuro), var(--morado-claro));
    color: var(--blanco);
    padding: 50px 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 3rem;
}

header p {
    font-size: 1.2rem;
    margin-top: 10px;
}

/* NAV */
nav {
    background-color: var(--morado-claro);
    display: flex;
    justify-content: center;
    padding: 15px 0;
}

nav a {
    color: var(--blanco);
    margin: 0 20px;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: var(--gris-claro);
}

/* MAIN */
main {
    padding: 40px 20px;
    max-width: 1000px;
    margin: auto;
}

/* SECCIÓN DE BIENVENIDA */
.welcome {
    background-color: var(--blanco);
    border-radius: 15px;
    padding: 40px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    margin-bottom: 40px;
}

.welcome h2 {
    color: var(--morado-oscuro);
    font-size: 2rem;
}

.welcome p {
    font-size: 1.1rem;
    margin-top: 15px;
}

/* SECCIÓN DE CONTACTO */
.contact {
    background-color: var(--blanco);
    border-radius: 15px;
    padding: 30px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    text-align: center;
}

.contact h3 {
    color: var(--morado-oscuro);
    font-size: 1.8rem;
    margin-bottom: 15px;
}

.contact p {
    font-size: 1.1rem;
    margin: 5px 0;
}

/* BOTONES */
.btn {
    display: inline-block;
    background-color: var(--morado-oscuro);
    color: var(--blanco);
    padding: 12px 25px;
    margin-top: 20px;
    border-radius: 10px;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background-color: var(--morado-claro);
}

/* FOOTER */
footer {
    background-color: var(--morado-oscuro);
    color: var(--blanco);
    text-align: center;
    padding: 20px;
    margin-top: 40px;
    font-size: 0.9rem;
}
</style>
</head>
<body>

<!-- HEADER -->
<header>
    <h1>Recetario Internacional</h1>
    <p>Explora recetas de todos los continentes</p>
</header>

<!-- NAVEGACIÓN -->
<nav>
    <a href="index.html">Inicio</a>
    <a href="principal.html">Página Principal</a>
    <a href="recetario.html">Recetario</a>
    <a href="#contacto">Contacto</a>
</nav>

<!-- CONTENIDO PRINCIPAL -->
<main>
    <!-- SECCIÓN DE BIENVENIDA -->
    <section class="welcome">
        <h2>¡Bienvenido a nuestro Recetario!</h2>
        <p>Descubre los sabores del mundo desde la comodidad de tu hogar. Explora recetas de América, Europa, Asia, África y Oceanía.</p>
        <a href="recetario.html" class="btn">Ver Recetario</a>
    </section>

    <!-- SECCIÓN DE CONTACTO -->
    <section id="contacto" class="contact">
        <h3>Contáctanos</h3>
        <p>📍 Dirección: Calle Río Papaloapan 501</p>
        <p>📧 Email: contacto@recetariointernacional.com</p>
        <p>📞 Teléfono: +52 55 1234 5678</p>
        <a href="mailto:contacto@recetariointernacional.com" class="btn">Enviar correo</a>
    </section>
</main>

<!-- FOOTER -->
<footer>
    &copy; 2026 Recetario Internacional. Todos los derechos reservados.
</footer>

</body>
</html>
