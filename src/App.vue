<script>
import AppHeader from "./components/AppHeader.vue"
import AppMain from "./components/AppMain.vue";
  export default {
    data() {
      return {

      }
    },
    components:{
    AppHeader,
    AppMain
}
  }
</script>

<template>
  <div class="container">

    <AppHeader></AppHeader>
    <AppMain></AppMain>
    
  </div>
    
  
</template>


<style scoped>
    
      .container{
        margin: 0 200px;
        
      }


</style>