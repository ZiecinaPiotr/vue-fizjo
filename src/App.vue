<template>
  <div id="app">
    <HeaderMenu />
    <Therapies />
    <Footer />
  </div>
</template>

<script>
import HeaderMenu from './components/HeaderMenu.vue'
import Therapies from './components/Therapies/Therapies.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    HeaderMenu,
    Therapies,
    Footer
  }
}
</script>

<style scoped>
#app {
  background: url("../img/light-grey-terrazzo.png"); /* www.toptal.com/designers/subtlepatterns/*/
	font-size: 25px;
	font-family: 'Lato', sans-serif;
}
</style>
