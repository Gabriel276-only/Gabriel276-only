<html lang="pt-br">
<head>
  <meta charset="UTF-8">
    <title>trabalhooo</title>
   
    <link rel="stylesheet" type="text/css"  href="estilo.css"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Righteous&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="//code.jquery.com/ui/1.13.2/themes/base/jquery-ui.css">
  <link rel="stylesheet" href="/resources/demos/style.css">
   
</head>
<body>
  <h1> Trabalho titulo do site</h1> 
<nav>
  <ul class="menu" >
		<li><a href="#">Home</a></li>
		<li><a href="#">Sobre</a></li>
	  		<li><a href="#">O que fazemos?</a>
	  		</li>
		<li><a href="#">Links</a></li>
		<li><a href="#">Contato</a></li>
    </ul>
</nav>
</head>  
 

<body>
<main>
  <div id="content">
	<div id="carrossel">
		<ul>
			<li>
				<img src="http://www.placehold.it/200x150" alt="Nome da Imagem" title="Nome da Imagem"/>
			</li>
			<li>
				<img src="http://www.placehold.it/200x150" alt="Nome da Imagem" title="Nome da Imagem"/>
			</li>
			<li>
				<img src="http://www.placehold.it/200x150" alt="Nome da Imagem" title="Nome da Imagem"/>
			</li>
			<li>
				<img src="http://www.placehold.it/200x150" alt="Nome da Imagem" title="Nome da Imagem"/>
			</li>
			<li>
				<img src="http://www.placehold.it/200x150" alt="Nome da Imagem" title="Nome da Imagem"/>
			</li>
		</ul>
	</div>
	<nav id="menu-carrossel">
    <button><a href="#" class="prev" title="Anterior">Anterior</a><button>
		<button><a href="#" class="next" title="Próximo">Próximo</a><button>
	</nav>
</div>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
  <script type="text/javascript" src="js/jcarousellite.js"></script>
  <script> $(function() {
    $("#carrossel"). jCarouselLite({
        btnPrev: '.prev',
        btnNext: '.next',
        visible: 3
    })
    })</script>

  </main>
 
</body>
</html>
