<script>
export default {
    
}
</script>

<template>
    <main class="bg-img">
        <div class="main-text">
            <span id="welcome">welcome to avada</span>
            <h2 id="second-part">have the night of your life</h2>
            <p id="lorem">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Enim pariatur corporis praesentium corrupti non sequi ipsum velit quaerat est. Obcaecati sint assumenda laudantium nostrum cupiditate cum quisquam perspiciatis vero delectus. Lorem ipsum dolor, sit amet consectetur adipisicing elit. </p>
            <div class="cards-container">
                        
                    <img id="card" src="/img/avada-nightclub-dancelounge-small.jpg" alt="">
                    
                    <span id="text-1-img">
                        dance lounge
                        <hr id="first-row">
                    </span>
                    <img id="card" src="/img/avada-nightclub-rooftoplounge-small.jpg" alt="">
                    <span id="text-2-img">
                        rooftop bar
                        <hr id="second-row">
                    </span>
                        
                    <img id="card" src="/img/avada-nightclub-viplounge-small.jpg" alt="">
                    <span id="text-3-img">
                        vip lounge
                        <hr id="third-row">
                    </span>
                    <img id="card" src="/img/avada-nightclub-events-small.jpg" alt="">
                    <span id="text-4-img">
                        resident dj
                        <hr id="fourth-row">
                    </span>
                
                

            </div>
        </div>

       
    </main>
</template>

<style scoped>
    .bg-img{
        background-image: url(/img/avada-nightclub-cloud-background.jpg);
        
        background-repeat: no-repeat;
        height: 100vh;
        width: calc(76vw - 11px);

        background-size: cover;
    }

    .main-text{
        display: flex;
        flex-direction: column;
        align-items: center;

        gap: 20px;

        
    }

    #welcome{
        text-transform: uppercase;
        font-weight: bold;
        font-size: 1.3em;

        margin-top: 130px;
        
        color: #46b1fd;
    }

    #second-part{
        font-size: 2.5em;
        
    }

    #lorem{
        font-size: 0.8em;

        margin: 20px 380px;
        text-align: center;
    }

    .cards-container{
        
        height: 500px;
        width: 800px;

        position: relative;
    }

    #card{
        height: calc((100% / 2) );
        width: calc(100% / 2 );

        

        
        
        
    }


    /*Stile prima scheda*/
    #text-1-img{
        position: absolute;
        left: 30px;
        top: 200px;

        font-size: 23px;
        font-weight: bold;

        
        
    }

    
    #first-row{
        height: 1px;
        background-color: #46b1fd;
        border: none;
        position: absolute;
        top: 16px;
        left: 152px;
        width: 218px;
    }
    /*____________________________________________*/


    /*Stile seconda scheda*/
    #text-2-img{
        position: absolute;
        
        left: 430px;
        top: 200px;

        font-size: 23px;
        font-weight: bold;
        
    }

    #second-row{
        height: 1px;
        background-color: #f63c81;
        border: none;
        position: absolute;
        top: 16px;
        left: 142px;
        width: 228px;
    }
    /*______________________________________________*/

    /*Stile terza scheda*/
    #text-3-img{
        position: absolute;
        
        left: 30px;
        bottom: 10px;

        font-size: 23px;
        font-weight: bold;
        
    }

    #third-row{
        height: 1px;
        background-color: #868518;
        border: none;
        position: absolute;
        top: 16px;
        left: 120px;
        width: 250px;
    }
    /*______________________________________________*/

    /*Stile quarta scheda*/
    #text-4-img{
        position: absolute;
        
        left: 430px;
        bottom: 10px;

        font-size: 23px;
        font-weight: bold;
        
    }

    #fourth-row{
        position: absolute;
        height: 1px;
        top: 16px;
        left: 130px;
        width: 240px;

        background-color: #d11894;
        border: none;

    }
    /*______________________________________________*/
    
    

    

        

        


</style>