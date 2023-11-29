<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        a {
            text-decoration: none;
            color: #fff;
        }

        .hero {
            background-color: #555;
            color: #fff;
            text-align: center;
            padding: 100px 0;
        }

        .hero h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 40px;
        }

        #ctaButton {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            font-size: 1.2em;
            border: none;
            cursor: pointer;
        }

        #ctaButton:hover {
            background-color: #45a049;
        }

        .feature, .contact {
            background-color: #f9f9f9;
            padding: 80px 0;
            text-align: center;
        }

        .feature h2, .contact h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .form input, .form textarea, .form button {
            width: 100%;
            margin-bottom: 20px;
            padding: 10px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
    <title>Meu Site Profissional</title>
</head>
<body>
    <header>
        <div class="container">
            <h1>Nome do Site</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Bem-vindo ao Nosso Site</h2>
            <p>Explore o que temos a oferecer.</p>
            <button id="ctaButton">Saiba Mais</button>
        </div>
    </section>

    <section id="sobre" class="feature">
        <div class="container">
            <h2>Sobre Nós</h2>
            <p>Descubra nossa história e missão.</p>
        </div>
    </section>

    <section id="contato" class="contact">
        <div class="container">
            <h2>Entre em Contato</h2>
            <p>Estamos ansiosos para ouvir de você.</p>
            <form>
                <input type="text" placeholder="Seu Nome">
                <input type="email" placeholder="Seu Email">
                <textarea placeholder="Sua Mensagem"></textarea>
                <button type="submit">Enviar Mensagem</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Nome do Site. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script>
        document.getElementById('ctaButton').addEventListener('click', function() {
            alert('Botão CTA clicado! Adicione sua lógica personalizada aqui.');
        });
    </script>
</body>
</html>
