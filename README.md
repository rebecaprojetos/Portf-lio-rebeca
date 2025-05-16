# Portfólio-rebeca
programação Alura
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Meu Portfólio</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Sou uma desenvolvedora apaixonada por tecnologia e inovação.</p>
    </section>

    <section id="projetos">
        <h2>Meus Projetos</h2>
        <div class="projeto">
            <h3>Projeto 1</h3>
            <p>Descrição do projeto.</p>
        </div>
        <div class="projeto">
            <h3>Projeto 2</h3>
            <p>Descrição do projeto.</p>
        </div>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Email: meuemail@email.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Meu Nome</p>
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
    background-color: #0077b6;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background: white;
    border-radius: 5px;
}

.projeto {
    border: 1px solid #ddd;
    padding: 10px;
    margin: 10px 0;
}

footer {
    text-align: center;
    padding: 10px;
    background: #0077b6;
    color: white;
} document.addEventListener("DOMContentLoaded", function() {
    console.log("Portfólio carregado!");
});