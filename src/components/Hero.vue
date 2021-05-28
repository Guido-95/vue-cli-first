<template>
    <div class="jumbotron">
        <img src="../assets/copertina.jpg" alt="Copertina"> 

            <div class="container-scritta-pugno">
                <div class="pugno">
                    <img src="../assets/pugno.png" alt="">
                </div>
                <span class="Acquista"> Acquistalo subito </span> 
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
        margin: 100px auto;
        text-align: left;
        background-position: 900px 13px;
        background-repeat: no-repeat;
        background-size: 853px 575px;
        transform: rotate(8deg);
        background-image: url('../assets/jumbotron.png');
        color: white;
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

    .container-scritta-pugno{
        transform: rotate(-8deg);
        margin-left: 70px; 
    }

    .Acquista{
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
    
     .container-scritta-pugno:hover .pugno{
        top: -80px;
        left: -235px;
        transition: 1s;
        opacity: 1;
    }

    .Acquista:hover {
        color: teal;
        margin-left: 58px;
        transition: ease-in 1s;
        background-color: yellow; 
    }

</style>