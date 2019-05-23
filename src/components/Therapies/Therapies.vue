<template>
  <div class="container" id="therapies">
   <div class="row">
    <figure class="col-8 offset-2 col-sm-8 offset-sm-2 col-lg-5 offset-lg-1">
      <a href="Terapia-manualna"><img class="img-fluid tail" src="../../../img/manual-therapy/terapia-manualna-3s.jpg" alt="Terapia manualna" /></a>
      <figcaption>Terapia manualna</figcaption>
    </figure>
    <figure class="col-8 offset-2 col-sm-8 offset-sm-2 col-lg-5 offset-lg-0">
      <a href="Kinesiotaping"><img class="img-fluid tail" src="../../../img/kinesiotaping/kinesiotaping2.jpg" alt="Kinesiotaping" /> </a>
      <figcaption>Kinesiotaping</figcaption>
    </figure>
    <figure class="col-8 offset-2 col-sm-8 offset-sm-2 col-lg-5 offset-lg-1">
      <a href="Suche-igłowanie"><img class="img-fluid tail" src="../../../img/dry-needling/iglowanie_nowe2.jpg" alt="Suche igłowanie" /> </a>
      <figcaption>Suche igłowanie</figcaption>
    </figure>
    <figure class="col-8 offset-2 col-sm-8 offset-sm-2 col-lg-5 offset-lg-0">
      <a href="Rehabilitacja-ortopedyczna"><img class="img-fluid tail" src="../../../img/orthopedic-rehabilitation/rehabilitacjaorto1.jpg" alt="Rehabilitacja ortopedyczna" /> </a>
      <figcaption>Rehabilitacja ortopedyczna</figcaption>
    </figure>
   </div> 
  </div>
</template>

<script>
export default {
  name: "Therapies"
}
</script>

<style scoped>
#therapies {
	padding-top: 150px;
}

figure {
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
