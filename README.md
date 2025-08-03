# Ejercicio1
<<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Bienvenidos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }

        .nav-left {
            display: flex;
            flex-direction: column;
        }

        .nav-links {
            margin-top: 5px;
        }

        .nav-links a {
            text-decoration: none;
            color: #2a5db0;
            margin: 0 10px;
            font-weight: bold;
        }

        .nav-links span {
            color: #000;
        }

        .image-placeholder {
            width: 50px;
            height: 50px;
            border: 2px solid #000;
            position: relative;
        }

        .image-placeholder::before,
        .image-placeholder::after {
            content: '';
            position: absolute;
            width: 2px;
            height: 100%;
            background-color: #000;
            top: 0;
            left: 50%;
            transform: rotate(45deg);
        }

        .image-placeholder::after {
            transform: rotate(-45deg);
        }
    </style>
</head>
<body>

    <div class="nav-container">
        <div class="nav-left">
            <div><strong>Bienvenidos</strong></div>
            <div class="nav-links">
                <a href="#">Home</a>
                <span>|</span>
                <a href="#">Estudiantes</a>
                <span>|</span>
                <a href="#">Administradores</a>
                <span>|</span>
                <a href="#">Acerca de</a>
            </div>
        </div>
        <div class="image-placeholder"></div>
    </div>

</body>
</html>