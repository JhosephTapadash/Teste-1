# Teste-1
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>The Legend of Zelda</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Mundo de The Legend of Zelda</h1>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="personagens.html">Personagens</a></li>
                <li><a href="contato.html">Contato</a></li>
                <li><a href="autores.html">Autores</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Sobre a Série</h2>
            <p>The Legend of Zelda é uma série de jogos de ação-aventura desenvolvida pela Nintendo.</p>
            <img src="zelda.jpg" alt="The Legend of Zelda">
        </section>
    </main>
    <footer>
        <p>&copy; 2024 The Legend of Zelda Fan Site</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
    <title>Personagens - The Legend of Zelda</title>
</head>
<body>
    <header>
        <h1>Personagens</h1>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="personagens.html">Personagens</a></li>
                <li><a href="contato.html">Contato</a></li>
                <li><a href="autores.html">Autores</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Personagens Principais</h2>
        <ul>
            <li>Link</li>
            <li>Zelda</li>
            <li>Ganondorf</li>
        </ul>
        <table>
            <tr>
                <th>Nome</th>
                <th>Tipo</th>
                <th>Poderes</th>
            </tr>
            <tr>
                <td>Link</td>
                <td>Herói</td>
                <td>Espada, Arco</td>
            </tr>
            <tr>
                <td>Zelda</td>
                <td>Princesa</td>
                <td>Magia</td>
            </tr>
        </table>
    </main>
    <footer>
        <p>&copy; 2024 The Legend of Zelda Fan Site</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
    <title>Contato - The Legend of Zelda</title>
</head>
<body>
    <header>
        <h1>Contato</h1>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="personagens.html">Personagens</a></li>
                <li><a href="contato.html">Contato</a></li>
                <li><a href="autores.html">Autores</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Envie-nos uma Mensagem</h2>
        <form action="#" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </main>
    <footer>
        <p>&copy; 2024 The Legend of Zelda Fan Site</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
    <title>Autores - The Legend of Zelda</title>
</head>
<body>
    <header>
        <h1>Autores</h1>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="personagens.html">Personagens</a></li>
                <li><a href="contato.html">Contato</a></li>
                <li><a href="autores.html">Autores</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Nossos Autores</h2>
        <p>Autor 1: João Silva - Estudante de Desenvolvimento Web.</p>
        <p>Autor 2: Maria Oliveira - Apaixonada por jogos e design.</p>
    </main>
    <footer>
        <p>&copy; 2024 The Legend of Zelda Fan Site</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: #fff;
    position: relative;
    bottom: 0;
    width: 100%;
}

table {
    width: 100%;
    border-collapse: collapse;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 8px;
    text-align: left;
}
