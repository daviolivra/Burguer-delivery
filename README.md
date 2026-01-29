# Burguer-delivery
Um repositório para ilustrar um pouco de um dos projetos mais requisitados 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="../src/css/style.css">
    <title>Página Inicial</title>
    <link rel="shortcut icon" href="../src/img/icone.png">
</head>
<body class="corpo-index">
    <nav class="cabecalho">
        <br><br>
        <a href="index.html" class="ativa">Início</a>
        <a href="pages/menu.html">Menu</a>
        <a href="pages/pedidos.html">Peça Aqui</a>
        <a href="pages/contato.html">Contato</a>
        <br><br><br>
    </nav>

    <div class="conteudo-inicio">
        <img src="../src/img/restaurante.png" alt="restaurante-blur" class="img-fundo">
        <img src="../src/img/logo_laranja.png" alt="logo-restaurante" class="logo-inicio">
        <h2>Bem-vindo ao Stacked Burger</h2>
    </div>

    <div class="container-infos">
        <h1>Sobre nós</h1>
        <p>O Stacked Burger é um restaurante especializado em hambúrgueres artesanais, oferecendo uma experiência única e saborosa para os amantes de comida. Mas ir ao Stacked é muito mais do que apenas pedir um lanche: é participar de uma verdadeira jornada gastronômica, onde cada ingrediente é escolhido a dedo e o conceito de "montar" seu hambúrguer é levado a sério.</p>
        <p>O Stacked Burger nasceu de uma paixão simples e uma frustração comum: encontrar um hambúrguer que fosse simultaneamente artesanal e perfeitamente equilibrado. Em maio de 2018, o Chef João Amado, um entusiasta da culinária de rua, decidiu transformar sua garagem em uma chapa experimental. Sua motivação central era resgatar a dignidade do hambúrguer, elevando-o de fast-food a uma experiência slow-food acessível.</p>
    </div>

    <div class="container-infos">
        <h1>Localização</h1>
        <p>O Stacked Burger está localizado no <strong>Shopping Patio Água Fria</strong></p>
        <p>Endereço: Av. Washington Soares, 3690, no bairro Parque Manibura, Fortaleza - CE, 60821-750.</p>
        <p>Venha nos visitar e experimente nossos deliciosos hambúrgueres artesanais!</p>

        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d248.81787224240864!2d-38.48062111350417!3d-3.7914579098257355!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7c74588d968f22d%3A0x613ce6b5bbabd4f!2sAv.%20Washington%20Soares%2C%203690%20-%20Edson%20Queiroz!5e0!3m2!1spt-BR!2sbr!4v1762110638976!5m2!1spt-BR!2sbr" width="1700" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

    <div class="container-infos">
        <h1>Avaliações</h1>
        <h2>Já comprou na Stacked Burger? Deixe sua avaliação: </h2>
        <!--Sistema de avaliação usando JS-->
        <ul class="avaliacao">
            <li class="star-icon ativo" data-avaliacao="1"></li>
            <li class="star-icon" data-avaliacao="2"></li>
            <li class="star-icon" data-avaliacao="3"></li>
            <li class="star-icon" data-avaliacao="4"></li>
            <li class="star-icon" data-avaliacao="5"></li>
        </ul>
        <!--Comentario de avaliação-->
        <form class="form-avaliacao" action="avaliacoes.php" autocomplete="off">
            <h3 style="color: black;">Deixe seu comentário:</h3>
            <textarea name="comentario" id="comentario" placeholder="Digite seu comentário aqui..."></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>
</body>
</html>
