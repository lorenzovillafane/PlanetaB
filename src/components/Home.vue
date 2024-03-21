<script>
import Inicio from '../components/Inicio.vue'
import Recetas from './Recetas.vue';
import About from './About.vue';
import Contact from './Contact.vue';


export default {
name: "Home",
  components: {
    Inicio,
	Recetas,
	About,Contact,
   
  }
  
}
</script>
<template>



<div class="panels">
	<div class="panel"><Inicio/></div>
	<div class="panel"><Recetas/></div>
	<div class="panel"><About/></div>
	<div class="panel"><Contact/></div>
</div>

</template>
<style >
@import url(../styles/homeStyles.css);
</style>