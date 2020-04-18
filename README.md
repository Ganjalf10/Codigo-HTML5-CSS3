<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<title>Proyecto para el curso de HTML5 y CSS3</title>
	<link rel="stylesheet" href="css/normalize.css">
	<link rel="stylesheet" href="css/estilos.css">


</head>
<body>
	
	<header class="encabezado" role="banner">
		<div class="contenedor">
			<a href="#" class="logo">
				<img src="images/logo.png" width="450" alt="Logo del sitio">
			</a>
			<nav role="navigation">
				<ul>
					<li><a href="-#">Nosotros</a></li>
					<li><a href="-#">Servicios</a></li>
					<li><a href="-#">Contactos</a></li>
				</ul>
			</nav>
		</div>
	</header> <!--Fin de encabezado-->

	<div class="presentacion">

		<div class="contenedor">

			<div class="introduccion-presentacion">
				<h1>Juliana Mendonca <br>
					<span>Profesora de Danza Contenporanea</span>
				</h1>

				<a href="#" class="galeria">Galeria</a>
			</div>

			<img src="images/juli-3.JPG" width="450" alt="">

		</div>	
	</div> <!-- Fin de Presentacion.-->

	<section class="acceso-rapido">
		<div class="contenedor">
				<h1>ACCESO RAPIDO</h1>
					<figure>
						<a href="#"><img src="images/face-negro.png" alt="Comunidad"></a>
						<figcaption><h2><a href="#">Comunidad</a></h2></figcaption>
					</figure>
					<figure>
						<a href="#"><img src="images/gmail-negro.png" alt="Email"></a>
						<figcaption><h2><a href="#">Email</a></h2></figcaption>
					</figure>
					<figure>
						<a href="#"><img src="images/youtube-negro.png" alt="YouTube"></a>
						<figcaption><h2><a href="#">Presentaciones</a></h2></figcaption>
					</figure>
					<figure>
						<a href="#"><img src="images/ubicacion-negro.png" alt="Ubicacion"></a>
						<figcaption><h2><a href="#">Ubicanos</a></h2></figcaption>
					</figure>
		</div>
	</section>    <!-- Fin de acceso-rapido-->

				<div class="bloque-contenido">
					<div class="contenedor">
						<main class="articulos" role="main">
							<h2>ULTIMAS NOTICIAS</h2>
							<article>
								<h1><a href="#">Liquidanza</a></h1>
									<p>Liquidanza is a dance form practiced in water created by Juliana Mendonca. Dancing in water is a healing experience that brings a powerful shift of awareness to our relationship with our bodies, our minds and our nature. As we dive into water, our weight changes and our movement slows down changing completly the possibilities for dance.</p>
								 	<video width="400" control autoplay loop poster="images/logo.png">
									<source src="video/juli.mp4" type="video/mp4"><source src="video/juli.webm" type="video/webm">	
									</video>
							</article>
								<article>
									<h1><a href="#">Formacion Academica</a></h1>
									<p>Venezuelan Contemporary Dance performer, choreographer and teacher. <br> Graduated with a degree in dance from University Institute of Caracas, Venezuela (IUDANZA - UNEARTE) in 2005, she also served as an instructor at the Performing Arts Department of the University of the Andes in Mérida, Venezuela (U.L.A.) (2012-2015); and at the Traditional Dance Program of the National University for the Arts (UNEARTE) (2008); Juliana also served as an independent Yoga and Latin Rhythms dance teacher. In 2011 she received certification as a Yoga instructor by the Physiology of Exercise Program of the University of the Andes (U.L.A.), Mérida, Venezuela.</p>
									<img src="images/juli-21.JPG" width="400" alt="">									
								</article>
								<article>
									<h1><a href="#"> Raiz de Agua</a></h1>
									<p> In 2005, Juliana co-founded Raíz de Agua, a music and dance company, which is her principal artistic endeavor. Since then, she has performed mostly as a solo artist with the Company and through dance has found a way to connect her creativity to spirit and nature, compounded with a unique feminine and artistic self-awareness. </p>
									<img src="images/juli-8.JPG" width="400" alt="">
								</article>
							</main>

							<aside class="complementario" role="complementary">
								<h2>PROXIMOS EVENTOS</h2>
								<ul>
									<li><a href="#">Liquidanza class in water created by Juliana Mendonca.</a></li>
									<li><a href="#">SCHEDULE: October 21. Every Monday. 
									7 - 8pm  Beginner.  8:15 - 9:15pm Intermediate.</a></li>
									<li><a href="#">Liquidanza class in water created by Juliana Mendonca.</a></li>
									<li><a href="#">SCHEDULE: October 21. Every Monday. 
									7 - 8pm  Beginner.  8:15 - 9:15pm Intermediate.</a></li>
									<li><a href="#">Liquidanza class in water created by Juliana Mendonca.</a></li>
									<li><a href="#">SCHEDULE: October 21. Every Monday. 
									7 - 8pm  Beginner.  8:15 - 9:15pm Intermediate.</a></li>
									<li><a href="#">Liquidanza class in water created by Juliana Mendonca.</a></li>
									<li><a href="#">SCHEDULE: October 21. Every Monday. 
									7 - 8pm  Beginner.  8:15 - 9:15pm Intermediate.</a></li>
									<li><a href="https://raizdeagua.com/">Proyecto Raiz de Venezuela-Mérida.</a></li>
								</ul>
							</aside>
						</div>
					</div> <!-- Fin de .bloque-contenido-->


					<section class="suscripcion">
						<div class="contenedor">
							<h2>Mantengase actualizado:</h2>
							<form action="#">
								<input type="text" name="nombre"  placeholder="Ingresa tu nombre" required>
								<input type="email" name="email"  placeholder="Ingresa tu email" required>
								<input type="submit" value="Registrate">
							</form>

						</div>

					</section> <!-- Fin de .suscripcion -->

					<footer class="piedepagina" role="contentinfo">
						<div class="contenedor">
						<small>Copyright 2020 Nombre Empresa</small>
						<nav>
							<ul>
								<li><a href="#">Politicas del Sitio</a></li>
								<li><a href="#">Preguntas frecuentes</a></li>
								<li><a href="#">Contactanos</a></li>
							</ul>
						</div>
					</nav>
					</footer> <!-- Fin de .piedepagina -->

					 <div class="social">
						<a href="#" title="Vamos a Instagram"><img src="images/instagram-negro.png" alt="Instagram"></a>
						<a href="#" title="Vamos a Linkedln"><img src="images/in-logo.png" alt="Linkedln"></a>
						<a href="#" title="Vamos a Whatsapp"><img src="images/wasap-negro.png" alt="Whatsapp"></a>
					</div> 
				</body>
				</html>
