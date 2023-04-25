<template>
  <main class="colums is-gapless is-multiline">
    <div class="column is-one-quarter">
      <barraLateral  />
    </div>
    <div class="column is-one-quarter">
     <Formulario />
    </div>
  </main> 
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import  barraLateral from './components/barraLateral.vue';
import Formulario from './components/formulario.vue';

export default defineComponent({
  name: 'App',
  components: {  
    barraLateral,
    Formulario
  }
});
</script>

<style>

</style>
