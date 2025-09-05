<index.html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Charlie Brown Jr. - Página Oficial</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/Charlie_Brown_Jr_logo.svg/800px-Charlie_Brown_Jr_logo.svg.png" alt="Charlie Brown Jr. Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#musicas">Músicas</a></li>
                <li><a href="#noticias">Notícias</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="sobre">
        <h1>Sobre a Banda</h1>
        <p>Charlie Brown Jr. foi uma banda brasileira de rock formada em Santos, São Paulo, em 1992. Conhecida por seu estilo musical que mistura rock, punk, reggae e rap, a banda conquistou uma legião de fãs com suas letras impactantes e energia no palco.</p>
    </section>

    <section id="musicas">
        <h1>Músicas</h1>
        <ul>
            <li><a href="https://www.youtube.com/watch?v=fdrCj8Ckw8o">Proibida pra Mim</a></li>
            <li><a href="https://www.youtube.com/watch?v=cqcfql6IQr4">Te Levar</a></li>
            <li><a href="https://www.youtube.com/watch?v=0iyfD4Z8WOU">Tudo de Bom</a></li>
        </ul>
    </section>

    <section id="noticias">
        <h1>Últimas Notícias</h1>
        <p>O legado de Charlie Brown Jr. continua vivo! A banda, embora tenha perdido seu vocalista Chorão, ainda inspira novas gerações com sua música única.</p>
    </section>

    <section id="contato">
        <h1>Contato</h1>
        <form action="#" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Charlie Brown Jr. - Todos os direitos reservados.</p>
    </footer>

    <script>
        // Exemplo simples de interação (altera cor de fundo do site ao clicar em uma música)
        document.querySelectorAll('a').forEach(item => {
            item.addEventListener('click', () => {
                document.body.style.backgroundColor = '#FF4C4C'; // Cor inspirada no logo da banda
            });
        });
    </script>
    /* Resetando alguns estilos padrões */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilo para o body */
body {
    font-family: 'Arial', sans-serif;
    background-color: #F1F1F1;
    color: #333;
}

/* Estilos do header */
header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header .logo img {
    width: 150px;
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #FF4C4C; /* Cor de destaque */
}

/* Estilos para as seções */
section {
    padding: 40px 20px;
    text-align: center;
}

section h1 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: #FF4C4C;
}

section p {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #555;
}

section ul {
    list-style: none;
    margin-top: 20px;
}

section ul li {
    margin: 10px 0;
}

section ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1.2rem;
    transition: color 0.3s;
}

section ul li a:hover {
    color: #FF4C4C;
}

/* Estilo para o formulário de contato */
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin-bottom: 10px;
    font-size: 1rem;
}

form input, form textarea {
    width: 300px;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1rem;
}

form button {
    background-color: #FF4C4C;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1rem;
}

form button:hover {
    background-color: #cc3a3a;
}

/* Estilo do rodapé */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
}

</body>
</html>
