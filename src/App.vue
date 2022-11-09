<template>
  <div class="bg-color">
    <AppTitle/>
    <AppHero/>
  </div>
    
 
</template>

<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';
// import AppHero from './components/AppHero.vue';
  export default {
    components:{
    AppTitle,
    AppHero
},
    data(){
      return{
       
      }
    },
    
  }
</script>

<style lang="css">
  .bg-color{
    background-color: black;
  }
</style>