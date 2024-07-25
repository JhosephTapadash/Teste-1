# Página Inicial
"""
<!DOCTYPE html>
<html>
<head>
    <title>Página Inicial</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao nosso site!</h1>
    </header>
    <nav>
        <ul>
            <li><a href="characters.html">Personagens</a></li>
            <li><a href="contact.html">Contato</a></li>
            <li><a href="authors.html">Autores</a></li>
        </ul>
    </nav>
    <main>
        <h2>Sobre o Jogo/Série/Biografia</h2>
        <p>Informações relevantes aqui...</p>
    </main>
    <footer>
        <p>© 2024 Nosso Site</p>
    </footer>
</body>
</html>
"""

# Página de Personagens
"""
<!DOCTYPE html>
<html>
<head>
    <title>Personagens</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Personagens</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Página Inicial</a></li>
            <li><a href="contact.html">Contato</a></li>
            <li><a href="authors.html">Autores</a></li>
        </ul>
    </nav>
    <main>
        <h2>Lista de Personagens</h2>
        <ul>
            <li>Personagem 1</li>
            <li>Personagem 2</li>
            <li>Personagem 3</li>
        </ul>
    </main>
    <footer>
        <p>© 2024 Nosso Site</p>
    </footer>
</body>
</html>
"""

# Página de Contato
"""
<!DOCTYPE html>
<html>
<head>
    <title>Contato</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Contato</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Página Inicial</a></li>
            <li><a href="characters.html">Personagens</a></li>
            <li><a href="authors.html">Autores</a></li>
        </ul>
    </nav>
    <main>
        <h2>Formulário de Contato</h2>
        <form>
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </main>
    <footer>
        <p>© 2024 Nosso Site</p>
    </footer>
</body>
</html>
"""

# Página dos Autores
"""
<!DOCTYPE html>
<html>
<head>
    <title>Autores</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Autores</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Página Inicial</a></li>
            <li><a href="characters.html">Personagens</a></li>
            <li><a href="contact.html">Contato</a></li>
        </ul>
    </nav>
    <main>
        <h2>Nossos Autores</h2>
        <p>Informações sobre os autores aqui...</p>
    </main>
    <footer>
        <p>© 2024 Nosso Site</p>
    </footer>
</body>
</html>
"""

# CSS
"""
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
}

header {
    background-color: #f8f9fa;
    width: 100%;
    padding: 20px 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    text-decoration: none;
    color: #007bff;
}

main {
    margin: 20px 0;
}

footer {
    background-color: #f8f9fa;
    width: 100%;
    padding: 20px 0;
    position: fixed;
    bottom: 0;
}
"""
