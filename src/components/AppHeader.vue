<script>
  export default {
    data() {
      return {

      }
    }
  }
</script>

<template>
    <div class="bg">

        
        
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
            <span id="vip">become a vip</span>
            <img id="view_club" src="/img/avada-nightclub-play-showreel.png" height="50px" alt="">
        </div>  

        
    </div>
    
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
    font-size: larger;
}
    .item{
        cursor: pointer;
    }


    #footer-up{
       
        display: flex;
        padding-top: 500px;
        align-items: center;
        flex-direction: column;
        
        
        
    }

    .title{
        background-color: #0000009c; 
        width: fit-content;

        border-top: 5px solid #46b1fd;
        
        padding: 70px 120px;
    }

    #vip{
        background-color: #f63c81;

        padding: 10px 30px;
        margin-top: -25px;

        text-transform: uppercase;
        font-weight: bold;

    }

    #view_club{
        margin-top: 50px;
    }
        
</style>