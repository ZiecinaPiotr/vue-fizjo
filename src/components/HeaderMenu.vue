<template>
	<nav class="navbar navbar-expand-lg fixed-top p-0 border-bottom shadow-sm rounded" id="navigation">
		<a class="navbar-brand col-9 col-sm-6 offset-sm-2 col-md-4 offset-md-2 col-lg-3" id="logoside" href="Fizjoterapia-Hubert-Kostka">
			<img id="logo" src="../../img/main-page/logoprzez.png" alt="Fizjoterapia-Hubert Kostka" />
		</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResidue" aria-controls="navbarResidue"
		 aria-expanded="false" aria-label="Toggle navigation">
			<span class="navbar-toggler-icon icon-th-list-1"></span>
		</button>
		<div class="collapse navbar-collapse" id="navbarResidue">
			<ul class="navbar-nav nav-fill mx-auto p-0">
				<li class="nav-item">
					<a class="nav-link " href="O-mnie">O mnie</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="Oferta">Oferta</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="Galeria">Galeria</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="Kontakt">Kontakt</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="Współpraca">Współpraca</a>
				</li>
			</ul>
		</div>
	</nav>
</template>

<script>
export default {
  name: "HeaderMenu"
}
</script>

<style scoped>
#navigation, .navbar .navbar-expand-lg .fixed-top .p-0 {
	background: url("../../img/tlomenu.jpg");
}

#logoside {
	margin: 0;
}

.navbar-brand {
	max-height: 110px;
}

.navbar-toggler-icon {
	font-size: 30px;
}

#logo {
	margin: 0;
	max-height: 120px;
	/* width: 100%; */
	text-align: center;
}

.nav-fill .nav-item {
	margin: auto 5px;
	padding: 0;
}

.nav-fill .nav-item .nav-link {
	color: rgb(22, 67, 212);
	font-size: 28px;
}

.nav-fill .nav-item .nav-link:hover {
	font-size: 30px;
	color: rgb(7, 118, 209);
	text-decoration: underline;
}

section {
	margin-top: 0px;
	height: auto;
}

.slidshow-container {
	width: 100%;
}

.slider {
	margin-top: 150px;
}


.slides {
	display: none;
	width: 100%;
}

.fade {
	animation-name: fade;
	animation-duration: 2s;
}

.fade:not(.show) {
    opacity: 1;
}

@keyframes fade {
	from{opacity: 0.4;}
	to{opacity: 1;}
}

.slide {
	border-radius: 40px;
	box-shadow: 5px 5px 20px #182019;
	opacity: 0.95;
}

.number {
  position: absolute;
  padding:  8px 16px;
  color:#f2f2f2;
}

.prev,.next {
	position: absolute;
	top: 37%;
	color: #f2f2f2;
	padding: 10px 20px;
	font-size: 28px;
	border-radius: 0 5px 5px 0;
	cursor: pointer;
}

.next {
	right: 15px;
	border-radius: 5px 0 0 5px;
}

.container-fluid .slider .slidshow-container a {
	color: #f2f2f2;
}

.prev:hover,.next:hover {
	background: rgba(0,0,0,0.6);
}

.dots {
	text-align: center;
	padding-top: 25px;
}

.dot {
	width: 13px;
	height: 13px;
	display: inline-block;
	background: rgb(22, 67, 212);
	padding: 15px;
	margin: 15px;
	border-radius: 50%;
	cursor: pointer;
}
.active,.dot:hover {
	background: rgb(168, 12, 12); 
}

#therapies {
	padding-top: 150px;
}

figure {
	padding: 0px;
	text-align: center;
}

.tail {
	max-height: 320px;
	width: 100%; 
	padding: 5px;
	margin: 2px;
	border-radius: 40px;
	box-shadow: 5px 5px 20px #182019;
	opacity: 0.90;
	
}

#therapies .tail:hover{
	opacity: 1;
	transition: 5s easy-in-out;
}

#therapies .row figure figcaption {
	text-align: center;
	font-style: italic;
	font-size: 30px;
	margin-top: 8px;
}
</style>
