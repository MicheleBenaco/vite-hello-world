<template>
  <div class="bg-color">
    <AppTitle/>
  </div>
    
 
</template>

<script>
import AppTitle from './components/AppTitle.vue';
  export default {
    components:{
      AppTitle
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