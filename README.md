<!DOCTYPE html>
<html>
<head>
	<title>Parallax</title>
	<meta charset="utf-8">
	
	
	<style type="text/css">

		/*Configuração padrão da página
		------------------------*/

		body, html{
			margin: 0;
			font: 16px "Lato", sans-serif;
			color: #777;
			height: 100%;
		}

		.conteudo{
			color: #777;
			background-color: white;
			text-align: justify;
			padding: 50px 80px;
		}

		h3{
			text-transform: uppercase;
			color: #111;
			text-align: center;
		}

		/*Efeito Parallax
		---------------*/
		.caixa1, .caixa2, .caixa3, .caixa4{
			position: relative;
			height: 100%;
			opacity: 0.7;
			background-repeat: no-repeat;
			background-size: cover;
			background-position: center;
			background-attachment: fixed;
		}
		.caixa1{
			background-image: url(imagens/imagem1.jpg);
		}

		.caixa2{
			background-image: url(imagens/imagem2.jpg);
		}

		.caixa3{
			background-image: url(imagens/imagem3.jpg);
		}

		.caixa4{
			background-image: url(imagens/imagem4.jpg);
		}

		.conteudo-titulo{
			position: absolute;
			left: 0%;
			top: 45%;
			width: 100%;
			text-align: center;
		}

		.conteudo-titulo span.titulo{
			background-color: #111;
			padding: 18px;
			font-size: 25px;
			letter-spacing: 5px;
			color: #fff;
			text-transform: uppercase;
		}

		p{
			margin-bottom: 20px;
		}px

	</style>
</head>
<body>

	<div class="caixa1">
	<div class="conteudo-titulo">
	<span class="titulo">PASSEIO DE BALÕES</span>
	</div>
</div>


	<div class="conteudo">
		<h3>Parallax</h3>
		<p>It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>

		<p>It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
	</div>

	<div class="caixa2">
		<div class="conteudo-titulo">
	<span class="titulo">PEGANDO A ESTRADA</span>
	</div>
	</div>

	<div class="conteudo">
		<h3>Parallax</h3>
		<p>It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>

		<p>It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
		It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
	</div>

	<div class="caixa3">
	<div class="conteudo-titulo">
	<span class="titulo">PÔR DO SOL</span>
	</div>
	</div>

	<div class="caixa4">
	<div class="conteudo-titulo">
	<span class="titulo">MONTANHAS</span>
	</div>
	</div>

</body>
</html>
