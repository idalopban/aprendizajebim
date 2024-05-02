<?php
// Si se envía el formulario de registro, redirigir a la página de bienvenida
if ($_SERVER["REQUEST_METHOD"] == "POST" && isset($_POST['submit'])) {
    header("Location: welcome.php");
    exit();
}
?>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crear redes de aprendizaje de BIM para compartir conocimientos y experiencias</title>
</head>
<body>
    <header>
        <img src="bim_logo.png" alt="Logo BIM">
        <h1>Bienvenido a nuestra comunidad de aprendizaje BIM</h1>
        <p>¡Construyendo juntos el futuro de la industria!</p>
    </header>
    <div class="container">
        <h2>¿Qué es BIM?</h2>
        <p>El Modelado de Información de Construcción (BIM) es una metodología que revoluciona la forma en que diseñamos, construimos y gestionamos proyectos de construcción. Al integrar información en un modelo digital inteligente, BIM permite a los profesionales de la construcción colaborar de manera más eficiente y tomar decisiones informadas en todas las etapas del ciclo de vida del proyecto.</p>

        <h2>Únete a nuestra red de aprendizaje</h2>
        <p>En nuestra comunidad, nos apasiona compartir conocimientos y experiencias sobre BIM. Ya seas un principiante curioso o un experto experimentado, hay un lugar para ti en nuestra red. Únete a nosotros para:</p>
        <ul>
            <li>Acceder a recursos educativos sobre BIM</li>
            <li>Participar en discusiones y debates en línea</li>
            <li>Colaborar en proyectos de aprendizaje prácticos</li>
            <li>Conectar con profesionales de ideas afines de todo el mundo</li>
        </ul>

        <h2>Nuestros servicios</h2>
        <p>Ofrecemos una amplia gama de servicios diseñados para ayudarte a aprovechar al máximo el potencial de BIM en tus proyectos:</p>
        <ul>
            <li>Consultoría BIM personalizada</li>
            <li>Capacitación y desarrollo profesional</li>
            <li>Implementación de software BIM</li>
            <li>Soporte técnico continuo</li>
        </ul>

        <form action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]); ?>" method="post">
            <button type="submit" name="submit" class="button">¡Únete a nuestra comunidad hoy mismo!</button>
        </form>
    </div>
</body>
</html>
