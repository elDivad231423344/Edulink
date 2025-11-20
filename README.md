# Edulink
Proyecto edulink
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>EduLink – Tutorías en Línea</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f5f5f5;
        }

        header {
            background: #3b82f6;
            padding: 20px;
            color: white;
            text-align: center;
        }

        nav {
            background: #1e3a8a;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            padding: 60px;
            background: white;
            text-align: center;
        }

        .hero h1 {
            color: #1e40af;
        }

        .btn {
            background: #2563eb;
            color: white;
            padding: 12px 20px;
            border-radius: 6px;
            text-decoration: none;
        }

        .section {
            padding: 40px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,.1);
        }

        footer {
            background: #1e3a8a;
            padding: 20px;
            color: white;
            text-align: center;
            margin-top: 30px;
        }

        input, select {
            padding: 10px;
            width: 100%;
            margin-bottom: 10px;
        }

        button {
            padding: 10px;
            background: #3b82f6;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>EduLink</h1>
    <p>Tu plataforma de tutorías personalizadas en línea</p>
</header>

<nav>
    <a href="#inicio">Inicio</a>
    <a href="#tutores">Tutores</a>
    <a href="#agendar">Agendar</a>
    <a href="#login">Iniciar Sesión</a>
</nav>

<!-- INICIO -->
<section class="hero" id="inicio">
    <h1>Bienvenido a EduLink</h1>
    <p>Encuentra tutores expertos y agenda tus clases fácilmente.</p>
    <a href="#tutores" class="btn">Ver Tutores</a>
</section>

<!-- LISTA DE TUTORES -->
<section class="section" id="tutores">
    <h2>Lista de Tutores</h2>

    <div class="card">
        <h3>María Gómez – Matemáticas</h3>
        <p>Experta en álgebra, cálculo y estadística.</p>
        <button onclick="alert('Has elegido a María Gómez')">Seleccionar Tutor</button>
    </div>

    <div class="card">
        <h3>Carlos Ruiz – Programación</h3>
        <p>Especialista en Python, JavaScript y desarrollo web.</p>
        <button onclick="alert('Has elegido a Carlos Ruiz')">Seleccionar Tutor</button>
    </div>

    <div class="card">
        <h3>Lucía Hernández – Inglés</h3>
        <p>Profesora certificada TOEFL y Cambridge.</p>
        <button onclick="alert('Has elegido a Lucía')">Seleccionar Tutor</button>
    </div>
</section>

<!-- AGENDAR TUTORÍA -->
<section class="section" id="agendar">
    <h2>Agendar Tutoría</h2>

    <div class="card">
        <form>
            <label>Nombre del Estudiante:</label>
            <input type="text" placeholder="Tu nombre">

            <label>Selecciona el Tutor:</label>
            <select>
                <option>María Gómez – Matemáticas</option>
                <option>Carlos Ruiz – Programación</option>
                <option>Lucía Hernández – Inglés</option>
            </select>

            <label>Fecha:</label>
            <input type="date">

            <label>Hora:</label>
            <input type="time">

            <button type="submit">Agendar</button>
        </form>
    </div>
</section>

<!-- LOGIN -->
<section class="section" id="login">
    <h2>Iniciar Sesión</h2>

    <div class="card">
        <form>
            <label>Correo electrónico:</label>
            <input type="email" placeholder="usuario@example.com">

            <label>Contraseña:</label>
            <input type="password" placeholder="******">

            <button type="submit">Entrar</button>
        </form>
    </div>
</section>

<footer>
    © 2025 EduLink – Plataforma de Tutorías en Línea
</footer>

</body>
</html>
