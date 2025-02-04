<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Mundo Literário</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Meu Mundo Literário</h1>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#reviews">Resenhas</a></li>
                <li><a href="#recomendacoes">Recomendações</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Bem-vindo ao Meu Mundo Literário</h2>
        <p>Aqui você encontra resenhas, recomendações e muito mais sobre o universo dos livros.</p>
    </section>

    <section id="reviews">
        <h2>Resenhas de Livros</h2>

        <!-- Resenha de "As Crônicas de Nárnia" -->
        <article class="review">
            <h3>As Crônicas de Nárnia - C.S. Lewis</h3>
            <img src="imagens/narnia.jpg" alt="Capa do livro As Crônicas de Nárnia" width="200">
            <p><strong>Gênero:</strong> Fantasia</p>
            <p><strong>Sinopse:</strong> A série conta a história de quatro irmãos que descobrem um mundo mágico chamado Nárnia, onde vivem criaturas fantásticas e enfrentam desafios épicos. O leão Aslam, uma figura central na trama, simboliza esperança e sacrifício.</p>
            <p><strong>Minha Opinião:</strong> "As Crônicas de Nárnia" é uma obra-prima da literatura infantojuvenil. Além de ser repleta de aventuras emocionantes, a série aborda temas profundos como fé, moralidade e coragem. Cada livro é único, mas todos estão interligados por uma narrativa rica e envolvente. Recomendo especialmente para quem gosta de mundos mágicos e personagens carismáticos.</p>
            <p><strong>Nota:</strong> ★★★★★ (5/5)</p>
        </article>

        <!-- Resenha de "Fundação" -->
        <article class="review">
            <h3>Fundação - Isaac Asimov</h3>
            <img src="imagens/fundacao.jpg" alt="Capa do livro Fundação" width="200">
            <p><strong>Gênero:</strong> Ficção Científica</p>
            <p><strong>Sinopse:</strong> Em um futuro distante, o matemático Hari Seldon desenvolve a psico-história, uma ciência capaz de prever o futuro de grandes civilizações. Quando ele prevê a queda do Império Galáctico, decide criar a Fundação, uma organização destinada a preservar o conhecimento humano e reduzir o período de caos que se seguirá.</p>
            <p><strong>Minha Opinião:</strong> "Fundação" é um clássico da ficção científica que explora temas como política, poder e tecnologia. A escrita de Asimov é direta e focada em ideias, o que pode ser um desafio para alguns leitores, mas é extremamente recompensadora para quem aprecia narrativas complexas. A construção do universo é impressionante, e as reflexões sobre o futuro da humanidade são surpreendentemente relevantes até hoje.</p>
            <p><strong>Nota:</strong> ★★★★☆ (4/5)</p>
        </article>
    </section>

    <section id="recomendacoes">
        <h2>Recomendações de Leitura</h2>
        <ul>
            <li><strong>Fantasia:</strong> "O Senhor dos Anéis" - J.R.R. Tolkien</li>
            <li><strong>Ficção Científica:</strong> "Duna" - Frank Herbert</li>
            <li><strong>Drama:</strong> "A Culpa é das Estrelas" - John Green</li>
        </ul>
    </section>

    <section id="contato">
        <h2>Entre em Contato</h2>
        <form action="enviar.php" method="post">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" rows="5" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Meu Mundo Literário. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 1rem 0;
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
    padding: 2rem;
    margin: 1rem auto;
    max-width: 800px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #0073e6;
}

.review img {
    float: left;
    margin-right: 15px;
    margin-bottom: 15px;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #0073e6;
    color: white;
}
