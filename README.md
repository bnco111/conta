<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarjeta de Contacto</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #2c3e50, #4ca1af);
            margin: 0;
        }
        .card {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
            text-align: center;
            max-width: 400px;
            position: relative;
            overflow: hidden;
        }
        .card::before {
            content: '';
            position: absolute;
            width: 100%;
            height: 8px;
            background: #4ca1af;
            top: 0;
            left: 0;
        }
        .icon {
            font-size: 60px;
            color: #4ca1af;
            margin-bottom: 10px;
        }
        .card h2 {
            margin: 10px 0;
            color: #2c3e50;
            font-size: 22px;
            font-weight: 600;
        }
        .card p {
            margin: 8px 0;
            color: #555;
            font-size: 16px;
        }
        .card p strong {
            color: #2c3e50;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="icon">📊</div>
        <h2>Especialista en Contabilidad</h2>
        <p><strong>Nombre:</strong> Johnson Cid N.</p>
        <p><strong>Teléfono:</strong> +56 986241483</p>
        <p><strong>Email:</strong> johncid1999@gmail.com</p>
        <p><strong>Horario:</strong> Lunes a Viernes, 9 AM - 6 PM</p>
    </div>
</body>
</html>
