# ChismesConalep
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>ChismesConalep</title>    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #007BFF;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .post {
            margin-bottom: 20px;
            border: 1px solid #ddd;
            padding: 10px;
            background-color: #fff;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ChismesConalep</h1>
    </header>
    <div class="container">
        <h2>Publica tu historia de forma anónima</h2>
        <form action="publicar.php" method="post">
            <label for="titulo">Título:</label><br>
            <input type="text" id="titulo" name="titulo" required><br><br>
            <label for="historia">Historia:</label><br>
            <textarea id="historia" name="historia" rows="4" required></textarea><br><br>
            <input type="submit" value="Publicar">
        </form>
    </div>
    <div class="container">
        <h2>Historias recientes</h2>
        <div class="post">
            <h3>Título de la historia 1</h3>
            <p>Texto de la historia 1...</p>
        </div>
        <div class="post">
            <h3>Título de la historia 2</h3>
            <p>Texto de la historia 2...</p>
        </div>
        <!-- Puedes repetir esta estructura para más historias -->
    </div>
</body>
</html>
