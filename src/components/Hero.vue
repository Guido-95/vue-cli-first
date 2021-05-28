<template>
    <div class="jumbotron">
        <img src="../assets/copertina.jpg" alt="Copertina"> 

            <div class="acquista">
                <div class="pugno">
                    <img src="../assets/pugno.png" alt="">
                </div>
                <span class="animazione"> Acquistalo subito </span> 
            </div>
    </div>
   
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style scoped>

    .jumbotron {
        width: 95%;
        display: flex;
        align-items: center;
        height: 500px;
        position: relative;
        margin: auto;
        text-align: left;
        border: 2px solid white;
        color: white;
        background-position: 900px 13px;
        background-repeat: no-repeat;
        background-size: 853px 575px;
        transform: rotate(8deg);
        background-image: url('../assets/jumbotron.png');
    }

    .jumbotron > img {
        position: absolute;
        cursor: pointer;
        top: 50px;
        left: 350px;
        transform: rotate(-16deg);
        font-size: 0;
        width: 20%; 
        border: 2px solid white;
    }
    .jumbotron > img:hover{
        border: 4px solid white;
        
    }

    .acquista{
        
        transform: rotate(-8deg);
        margin-left: 70px;
        
    }

    .animazione{
        position: relative;
        padding: 20px;
        cursor: pointer;
        font-size: 20px;
        border: 1px solid white;
        display: inline-block;
    }

    .pugno{
        position: absolute;
        top: -79px;
        left: -350px;
        width: 300px;
    }
    .pugno img{
        width: 100%;
    }
    
     .acquista:hover .pugno{
        top: -80px;
        left: -235px;
        transition: 1s;
        opacity: 1;
    }

    .animazione:hover {
        color: teal;
        margin-left: 58px;
        transition: ease-in 1s;
        background-color: yellow;
        
    }

 
    



</style>