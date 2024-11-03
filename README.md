<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Moda</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <h1>Moda e Estilo</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#tendencias">Tendências</a></li>
                <li><a href="#produtos">Produtos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Página Inicial -->
    <section id="home">
        <h2>Bem-vindo ao nosso site de moda!</h2>
        <p>Descubra tendências e produtos que irão transformar seu guarda-roupa.</p>
        <a href="#produtos" class="btn">Ver Coleção</a>
    </section>

    <!-- Sobre Nós -->
    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Somos apaixonados por moda e estamos aqui para inspirar seu estilo com as últimas tendências.</p>
    </section>

    <!-- Tendências -->
    <section id="tendencias">
        <h2>Tendências de Moda</h2>
        <p>Veja o que está em alta no mundo da moda e como você pode incorporar essas tendências no seu estilo.</p>
    </section>

    <!-- Produtos -->
    <section id="produtos">
        <h2>Produtos</h2>
        <div class="produto">
            <img src="produto1.jpg" alt="Produto 1">
            <p>Descrição do Produto 1</p>
        </div>
        <div class="produto">
            <img src="produto2.jpg" alt="Produto 2">
            <p>Descrição do Produto 2</p>
        </div>
    </section>

    <!-- Contato -->
    <section id="contato">
        <h2>Contato</h2>
        <form action="#">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Moda e Estilo. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
