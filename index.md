<html>

<head>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8">
	<title>Oubangi Chari - Royan</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="author" content="Oubangichari">
	<meta name="description" content="Page de présentation d'Oubangichari, maison de vacances à Royan">
	<link rel="icon" href="img/sun.png">
	<meta name="keywords" content="Oubangichari, location, Royan">
	<link rel="stylesheet" href="css/bootstrap-3.3.7.min.css">
	<link rel="stylesheet" href="css/oubangichari.css">
	<script src="js/jquery-3.1.1.min.js"></script>
	<script src="js/bootstrap-3.3.7.min.js"></script>
	<!-- <script src="oubangichari.js" type="text/javascript"></script> -->

</head>


<body>

<script type="text/javascript">
	$(document).ready(function(){
		$('#myCarousel').carousel({
		    interval: false
		}); 
	});
</script>


<header >
	<img class="center" src="img/accueil.jpg" alt="" style="width: 10%; height: 10%">
	<h1>Oubangi Chari</h1>
	<p>Maison de vacances à Royan</p>
	<a href="#contact"  >
		<button id="contactHome"> 
			<img border="0" alt="" src="img/email_icon.png" width="50" height="50">&nbsp; Contact &nbsp;
			<img border="0" alt="" src="img/phone_icon.png" width="50" height="50">
		</button>
	</a>
</header>


<div class="contenu">

	<div id="columnsWrapper">
		<div class="section">
			<h2 id="description">Description</h2>
			Au calme, mais proche de la plage et des commerces (marché du parc), Oubangi Chari est une petite maison de deux chambres, agrémentée d'une veranda, d'un jardin et d'une terrasse ombragée.

			      
			<h2 id="photos">Photos</h2>
			<div id="myCarousel" class="carousel slide" data-ride="carousel">
				<!-- Indicators -->
				<ol class="carousel-indicators">
					<li data-target="#myCarousel" data-slide-to="0" class="active"></li>
					<li data-target="#myCarousel" data-slide-to="1"></li>
				</ol>

			 	<!-- Wrapper for slides -->
			 	<div class="carousel-inner" role="listbox">
					<div class="item active">
						<img src="img/maison-vue-d-ensemble.jpg" alt="Vue d'ensemble">
						<div class="carousel-caption">
							<h3>Vue d'ensemble</h3>
							<p>Une petite maison confortable</p>
						</div>
					</div>
					<div class="item">
						<img src="img/jardin.jpg" alt="Jardin">
						<div class="carousel-caption">
							<h3>Jardin</h3>
							<p>Se rafraîchir à l'ombre, ou profiter du soleil, c'est comme on veut !</p>
						</div>
					</div>
				</div>

				  <!-- Left and right controls -->
				<a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
					<span class="iconeCentree" aria-hidden="true">
						 <img src="img/glyphicons-225-chevron-left.png" alt="">
					</span>
					<span class="sr-only">Previous</span>
				</a>
				<a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
					<span class="iconeCentree" aria-hidden="true">
						<img src="img/glyphicons-224-chevron-right.png" alt="">
					</span>

					<span class="sr-only">Next</span>
				</a>
			</div>
		</div>


		<div class="section">
			<h2  id="localisation">Localisation</h2>
			<!-- <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2790.646981174878!2d-1.0097244106184464!3d45.61773773518419!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48017673794cf55f%3A0x50df63eaef416d6b!2sAll%C3%A9e+des+Marronniers%2C+17200+Royan!5e0!3m2!1sfr!2sfr!4v1488452295728" width="100%" height="360" frameborder="0" style="border:0" allowfullscreen></iframe> -->

			<h2 id="agenda">Disponibilités</h2>
			<!-- <iframe src="https://calendar.google.com/calendar/embed?src=oubangichari%40gmail.com&showTz=0&showTitle=0&amp;showPrint=0&amp;showTabs=0&amp;showCalendars=0&amp;height=300&amp;wkst=7&amp;bgcolor=%23FFFFFF&amp;ctz=Europe%2FParis" style="border-width:0" width="100%" height="360" frameborder="0" scrolling="no"></iframe> -->
		</div>
	</div>

	<div class="reserver">
		<h2 id="contact">Contact et réservation</h2>
		<ul >
			<li>
				<a href="mailto:oubangichari@gmail.com" class="contactFrame" id="showEmailAdress"> 
					<img border="0" alt="Contacter par mail" src="img/email_icon.png" width="50" height="50">
					<br>
					<i>  Cliquer pour envoyer un mail ou
					<br>
					passer le curseur pour voir l'adresse</i>
				</a>
				
			</li>
			<li >
				<div id="showPhoneNumber" class="contactFrame">
					<img border="0" alt="Voir le numéro de téléphone" src="img/phone_icon.png" width="50" height="50" class="iconeCentree">
					<br>
					<i> Passer le curseur pour voir </i>
					<br>
					Numéro de téléphone :
					<br>
				</div>
			</li>
		</ul>
	</div>
</div>


</body>

</html>





