<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página del Ojo Rojo</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
        }

        img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        h1 {
            margin-bottom: 30px;
            font-size: 24px;
        }

        .button-container {
            display: flex;
            gap: 15px;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: red;
            color: white;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>

    <img src="https://example.com/eye.png" alt="Ojo Rojo">
    <h1>Bienvenido a la Página del Ojo Rojo</h1>
    <div class="button-container">
        <button onclick="alert('Iniciar Sesión')">Iniciar sesión</button>
        <button onclick="alert('Crear Cuenta')">Crear cuenta</button>
    </div>

</body>
</html>
