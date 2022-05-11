# Html-e-CSS-
Estudos de HTML e CSS, minha primeira página

<!DOCTYPE html>

<html lang="pt-br">
	
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width">
		<title>Barbearia Pallone</title>
		
		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
 		<link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
		
		<style>

		</style>

	</head>
	
	<body>	
		<header>
			<div class="caixa">
				<h1><img class="logo-alura" src="logo1.png" alt="Logo da Barbearia Alura"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="contatos.html">Contatos</a></li>
					</ul>
				</nav>
			</div>	
		</header>

		<img class="banner" src="barbeariatop.jpg">
		
		<main>
			<section class="principal">
				<h2 class="titulo-principal">Sobre a Barbearia Pallone</h2>
				<img class="utensilios" src="utensilios.jpg" alt="Utensilios de um Barbeiro">

				<p>Localizada no coração da cidade de Ribeirão Bonito a <strong>Barbearia Pallone</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. Fundada em 2022, a Barbearia Pallone já é destaque na cidade e conquista novos clientes a cada dia.</p>

				<p id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes"</strong>.</em></p>

				<p>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</p>
			</section>

			<div class="barbearia-imagem-2">

				<img class="imagem-2" src="barbeariafoto2.jpg" alt="Imagem da Barbearia">
				
			</div>

			<section class="mapa">
				<h3 class="titulo-principal">Nosso estabelecimento</h3>
                <p>Nosso estabelecimento está localizado no coração da cidade.</p>

                <div class="mapa-conteudo">
                	<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d34797.85932903112!2d-46.572502595902016!3d-23.5442106475252!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5a2b2ed7f3a1%3A0xab35da2f5ca62674!2sCaelum%20-%20Escola%20de%20Tecnologia!5e0!3m2!1spt-BR!2sbr!4v1652215015021!5m2!1spt-BR!2sbr" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">	
                	</iframe>
                </div>	
			</section>

			<section class="beneficios">
				<h3 class="titulo-principal">Benefícios</h3>
				
				<div class="conteudo-beneficios">
					<ul class="lista-beneficios">
						<li class="itens">Atendimento aos Clientes</li>
						<li class="itens">Espaço diferenciado</li>
						<li class="itens">Localização</li>
						<li class="itens">Profissionais Qualificados</li>
						<li class="itens">Pontualidade</li>
						<li class="itens">Limpeza</li>
					</ul><img src="beneficios.jpg" class="imagem-beneficios">
				</div>

				<div class="video">
					<iframe width="100%" height="315" src="https://www.youtube.com/embed/wcVVXUV0YUY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
					</iframe>
				</div>	
		 	</section>
		</main>

	 	<footer>
			<img src="logo-branco.png" alt="Logo da Barbearia Alura">
			<p class="copyright">&copy; Copyright Barbearia Alura - 2022</p>
		</footer>
	</body>

</html>


\*-------------------------------------------CSS-------------------------------------------------*\
body {

	font-family: 'Montserrat', sans-serif;

}

header {
	
	background:linear-gradient(#FEFEFE #BBBBBB);
	padding: 20px 0;

}

.logo-alura{

	width: 27%;

}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;


}

nav {

	position: absolute;
	top: 110px;
	right: 0px;
}
nav li {

	display: inline;
	margin: 0 0 0 15px;
}

nav a {

	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 28px;
	text-decoration: none;


}

nav a:hover {

	color: #C78C19;
	text-decoration: underline;

}

.produtos {

	width: 940px;
	margin: 0 auto;
	padding: 50px 0;

}

.produtos li {

	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
	padding: 30px 20px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;


}

.produtos li:hover {

	border-color: #C78C19;
	border-width: 3px;

}

.produtos li:active {

	border-color: #088C19;

}

.produtos li:hover h2 {

	font-size: 35px;

}

.produtos h2 {

	font-size: 30px;
	font-weight: bold;

}

.produto-descricao{

	font-size: 18px;

}


.produto-preco {

	font-size: 22px;
	font-weight: bold;
	margin: 10px 0 0; //margin-top:
}

footer {

	text-align: center;
	background: url(bg.jpg);
	padding: 40px 0;
	

}

.copyright {

	color: #FFFFFF;
	font-size: 13px;
	margin: 20px 0 0;
}

main {


}

form {

	margin: 40px 0;

}

form label, form legend {

	display: block;
	font-size: 20px;
	margin: 0 0 10px;

}

.input-padrao {

	display: block;
	margin: 0 0 20px;
	padding: 10px 25px;
	width: 50%;
}

.checkbox{

	margin: 20px 0;
	
}

.enviar {

	width: 40%;
	padding: 15px 0;
	background: orange;
	color: white;
	font-weight: bold;
	font-size: 18px;
	border: none;
	border-radius: 5px;
	transition: 1s all;
	cursor: pointer;

}

.enviar:hover {

background: darkorange;
transform: scale(1.1);

}

table{

	margin: 20px 0 40px;

}

thead {
	background: #555555;
	color: white;
	font-weight: bold;
}

td, th {

	border: 1px solid #000000;
	padding: 8px 15px;

}








/* ---------------------------------CSS da página inicial ----------------------------------------------*/ 

.banner {

	width: 100%;
	box-shadow: 15px 15px 30px 0 #000000;

}

.titulo-principal {

	text-align: center;
	font-size: 3em;
	margin: 1em 0;
	clear: left;
	color: rgba(0, 0, 0, 0.9);
}

.principal	{

	padding: 3em 0;
	background: #FEFEFE;
	width: 940px;
	margin: 0 auto;
	font-size: 20px;

}

.principal p {

	margin: 0 0 1em;
}

.principal strong {

	font-weight: bold;

}

.principal em {

	font-style: italic;


}

.principal em strong {

	text-shadow: 2px 2px 8px #000000;
}

.utensilios{ 
	
	width: 120px;
	float: left;
	margin: 0 20px 20px 0;
	box-sizing: border-box;
	border: 1px solid #000000;
	border-radius: 5px;

 }

.barbearia-imagem-2 {

	text-align: center;
	opacity: 1;
	transition: 700ms;
	width: 940px;
	margin: 0 auto 60px;
	box-sizing: border-box;
	border: 3px solid #000000;
	border-radius: 10px;
	box-shadow: 20px 20px 40px 0 #000000;

}

.barbearia-imagem-2:hover {
	transition: 700ms;
	opacity: 0.9;
}

.imagem-2 {

	width: 100%
	
}

.mapa {

	padding: 3em 0;
	background: linear-gradient(#FEFEFEFE, #888888);
	display: block;	

}

.mapa p {

	margin: 0 0 2em;
	text-align: center;
	font-size: 20px;

}

.mapa-conteudo{

	width: 940px;
	margin: 0 auto;	
	box-shadow: 15px 15px 30px 0 #000000;

}


.beneficios {

	padding: 3em;
	background: linear-gradient(#888888, #363636); 

}

.conteudo-beneficios {

	width: 640px;
	margin: 0 auto;

}

.lista-beneficios {

	width: 40%;
	display: inline-block;
	vertical-align: top;
	font-size: 17px;

}
.itens {

	line-height: 1.5;

}

.itens:first-child {

	font-weight: bold;

}
.itens:before{

	content: "★";

}

.imagem-beneficios {

	width: 60%;
	box-sizing: border-box;
	border: 1px solid #000000;
	border-radius: 10px;
	box-shadow: 15px 15px 40px 0 #000000;


}

.imagem-beneficios:hover {

	transition: 700ms;
	border-color: #C78C19;
	border-width: 3px;

}

.video {

	width: 560px;
	margin: 5em auto;
	box-shadow: 15px 15px 30px 0 #000000;
}

.video:hover {

	transition: 1000ms;
	box-shadow: 15px 15px 30px 0 #C78C19;

}

@media screen and (max-width:480px) {

	.caixa, .principal, .barbearia-imagem-2, .conteudo-beneficios, .mapa-conteudo, .video {
    width: auto;
	}

	h1 {
    text-align: center;
	}
	
	nav {
    position:static;
	}
	
	.lista-beneficios, imagem-beneficios {
    width: 100%
	}
}
