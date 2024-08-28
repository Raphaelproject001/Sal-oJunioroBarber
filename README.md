
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Júnior Barber - Salão de Beleza</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #fff;
            background-color: #003366; /* Azul escuro */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #002244; /* Azul mais escuro */
            padding: 10px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px;
            margin: 0 15px;
            background-color: #004080; /* Azul médio */
            border-radius: 5px;
        }
        nav a:hover {
            background-color: #0056b3; /* Azul mais claro */
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            border-bottom: 2px solid #004080; /* Azul médio */
            padding-bottom: 5px;
        }
        .portfolio img {
            max-width: 100%;
            height: auto;
            display: block;
            margin-bottom: 10px;
        }
        footer {
            background-color: #002244; /* Azul mais escuro */
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .translate {
            text-align: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Júnior Barber</h1>
        <p>Seu salão de beleza na Vila Pelo Sinal</p>
    </header>
    
    <nav>
        <a href="#home">Início</a>
        <a href="#portfolio">Portfólio</a>
        <a href="#history">Histórico</a>
        <a href="#announcement">Anúncio</a>
    </nav>
    
    <div class="container">
        <div id="home" class="section">
            <h2>Bem-vindo ao Júnior Barber</h2>
            <p>Estamos localizados na Vila Pelo Sinal, próximo ao Trevo do Horto, ao lado da Caixa D'água. Venha conferir nossos serviços de alta qualidade!</p>
            <p>Endereço: Vila Pelo Sinal, próximo ao Trevo do Horto, ao lado da Caixa D'água.</p>
        </div>
        
        <div id="portfolio" class="section portfolio">
            <h2>Portfólio</h2>
            <img src="exemplo1.jpg" alt="Corte de cabelo masculino">
            <img src="exemplo2.jpg" alt="Barba bem feita">
            <!-- Adicione mais imagens conforme necessário -->
        </div>
        
        <div id="history" class="section">
            <h2>Histórico</h2>
            <p>O Júnior Barber é um salão de beleza dedicado a oferecer os melhores serviços de corte e barbearia. Fundado com a missão de proporcionar um atendimento de excelência, nosso salão conta com profissionais altamente qualificados e um ambiente acolhedor.</p>
        </div>
        
        <div id="announcement" class="section">
            <h2>Anúncio</h2>
            <p>Aproveite nossas promoções especiais! Consulte nossos preços e agende seu horário.</p>
        </div>
        
        <div class="translate">
            <button onclick="window.open('https://translate.google.com/', '_blank')">Traduzir Página</button>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2024 Júnior Barber. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
