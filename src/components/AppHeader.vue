<script>
  export default {
    data() {
      return {

      }
    }
  }
</script>

<template>
    <header class="bg">

        
        <div class="link-list">
            
            <ul id="list">
                <li class="item">home</li>
                <li class="item">the club</li>
                <li class="item">events</li>
                <div>
                    <img src="/img/avada-nightclub-logo.png" class="logo" alt="">
                </div>
                <li class="item">jobs</li>
                <li class="item">news</li>
                <li class="item">contact us</li>
            
                    
                    
                    
                
            </ul>
            
            
        </div>

        <div id="footer-up">
            <h1 class="title">making memories all night long</h1>
        </div>
    
    </header>
</template>

<style scoped>

    .bg{
        background-image: url(/img/avada-nightclub-home-hero.jpg);
        background-size: contain;
        background-repeat: no-repeat;
        height: 100vh;
        
    }


    #list{
        display: flex;
        gap: 50px;
        align-items: center;
        justify-content: center;

        list-style-type: none;

        text-transform: uppercase;
        font-weight: bold;
    }

    li:hover{
    color: #f63c81;
    border-bottom: 2px solid #f63c81;
}
    .item{
        cursor: pointer;
    }


    .title{
        
        text-align: center;
        padding-top: 600px;
        
        
    }
</style>