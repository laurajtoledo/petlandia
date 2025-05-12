<!DOCTYPE  html>
<html lang="pt-br">
	<head>
		<meta charset="utf-8">
		<title>Petlândia</title>


		<meta name="viewport" content="width=device-width, initial-scale=1">
		<meta name="description" content="Pet Shop especializado em Banho e Tosa e Atendimento Veterinário.">
		<meta name="keywords" content="Pet Shop, Banho e Tosa, Atendimento Veterinário">
		<meta name="robots" content="index, follow">
		<link rel="stylesheet" href="css/estilos.css">
		<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">
		<link rel="preconnect" href="https://fonts.gstatic.com">
		<link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;700&display=swap" rel="stylesheet">
		<link rel="preconnect" href="https://fonts.gstatic.com">
		<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
        <link rel="preconnect" href="https://fonts.gstatic.com">
        <link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap" rel="stylesheet">
		<link rel="icon" href="img/logoMenor.png">
	</head>
	<body>
		<header  class="cabecalho">
			<a href="index.html"><h1 class="logo">Petlândia</h1></a>

	<!-- CRIANDO O BOTÃO PARA O MENU -->
			<button class="btn-menu"> <i class="fa fa-bars fa-lg"></i></button>

	<!-- CRIANDO O MENU UTILIZANDO JQUERY PARA CONTROLAR A EXIBIÇÃO DESTE MENU -->
			<nav class="menu"> 
				<a class="btn-close"><i class="fa fa-times"></i></a>
				<ul>
					<li><a href="#home">Home</a></li>
					<li><a href="#serv">Serviços</a></li>
					<li><a href="#sob">Sobre</a></li>
					<li><a href="#contatos">Contatos</a></li>
				</ul>
			</nav>		
		</header>

    <!-- CRIANDO UM BANNER -->
    <a name="topo"></a>
    <div id="home" class="banner ">
    	<div class="tittle">
    		<h2> SEJAM BEM VINDOS A PETLÂNDIA , O MUNDO DOS PETS! </h2>
    		<h3> Em nosso Petshop Online você encontra recursos dos mais diversos e qualificados, para cuidar e confortar o seu bichinho, dando a ele mais conforto e carinho. </h3>
    	</div>
    </div>

    <!-- CRIANDO OS SERVIÇOS -->
    <main class="servicos">
        <a name="serv"></a>
        <h2>Conheça nossos serviços!</h2>
    	<article class="servico">
    		<a href="#"><img src="img/banho.jpg" alt="Banho e Tosa"></a>
    		<div class="inner">

    <!-- ADICIONANDO TEXTOS E IMAGENS AOS SERVIÇOS -->
    			<a href="#"> Banho e Tosa </a>
    			<p>Nossa equipe possui profissionais da área para cuidar do seu animalzinho. Em nosso banho e tosa utilizamos procedimentos de estética altamente qualificados e um cuidado especial entre o profissional e seu bichinho.
				Em nosso banho e tosa inclui: limpeza nas áreas da orelha, corte de unhas, hidratação dos pelos, corte na máquina, entre outros.</p>
    	</article>
    	<article class="servico">
    		<a href="#"><img src="img/petsitter.jpg" alt="Pet Sitter"></a>
    		<div class="inner">
    			<a href="#">Pet Sitter </a>
    			<p> Temos babá de animais para o seu cachorro não precisar sair de casa. As babás geralmente ficam responsáveis pelo passeio, pela alimentação e por outras atividades combinadas com os tutores. Pode ser uma excelente opção em épocas de viagem caso seu pet não se adapte bem aos hotéis ou ao convívio com outros animais.</p>
    	</article>
    	<article class="servico">
    		<a href="#"><img src="img/veterinario1.jpg" alt="Atendimento Veterinário"></a>
    		<div class="inner">
    			<a href="#">Atendimento Veterinário</a>
    			<p> Sempre que seu pet apresenta algum comportamento fora do comum, a recomendação é leva-lo ao veterinário. Na Petlândia não poderia faltar o atendimento e carinho que seu pet precisa, com veterinários especializados em várias áreas da medicina veterinária, a fim de oferecer melhor tratamento para seu animalzinho de estimação.</p>
    	</article>
    	<article class="servico">
    		<a href="#"><img src="img/planosaude.jpg" alt="Plano de Saúde"></a>
    		<div class="inner">
    			<a href="#">Plano de Saúde</a>
    			<p>A Petlândia oferece ampla rede de hospitais e veterinárias com um alto grau de especialização, em todo o território nacional, várias modalidades de planos e cobertura com todas as especialidades médicas veterinárias, que seu pet irá precisar ao longo de sua vida. É mais que um plano, é um ato de amor pelo seu bichinho.</p>
    	</article>
    </main>

    <!-- CRIANDO O SOBRE-->
    
    <div class="sobre">
        <h2 id="sob">Sobre nós!</h2>
        <h3>Isabela Nunes, Isabella Coutinho, Laura Toledo e Taíssa Mayara são as CEOs da Petlândia, fundada em 2020 devido ao grande amor pelos bichinhos, nós decidimos criar este petshop online para cuidarmos desses animais que tanto nos demonstram carinho todos os dias. Nossa área de atuação é voltada para o bem-estar dos animais. Com nossos serviços diferenciados, seu pet receberá muita atenção e amor e para nós é um prazer cuidar do seu animalzinho de estimação. Agradecemos pela confiança em nossos serviços.</h3>
    </div>

    <!-- CRIANDO O CONTATO -->
    <div class="contato">
        <h2 id="contatos">Contate-nos!</h2>
        <h4>Estamos localizados em:</h4>
            <h4><img src="img/local.png">Landmark Nações Unidas - Av. das Nações Unidas, 12399, 10° andar - Cidade Monções, São Paulo - SP, 04578-000</h4>
            <h4>Telefone: (11)3245-6685 </h4>
    </div>

    <!-- CRIANDO O RODAPÉ-->
    <footer class=" rodape">
        <div class="social-icons">
            <a href="#"><i class="fa fa-facebook"></i></a>
            <a href="#"><i class="fa fa-twitter"></i></a>
            <a href="#"><i class="fa fa-google"></i></a>
            <a href="#"><i class="fa fa-instagram"></i></a>
            <a href="#"><i class="fa fa-envelope"></i></a>
        </div>
        <p class="copyright"> Copyright © Petlândia 2021. Todos os direitos reservados. </p>
        <br></br>
        <a href="#topo">Voltar para o Home</a>
    </footer>


   	<!-- CONTROLANDO OS EVENTOS DO MENU COM JQUERY -->
	<script src="http://code.jquery.com/jquery-1.12.0.min.js"></script>
	<script>
	$(".btn-menu").click(function(){
		$(".menu").show();
	});
	$(".btn-close").click(function(){
		$(".menu").hide();
	});
	</script>
	</body>

</html>
