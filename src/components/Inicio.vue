<script>


</script>
<template>
    <section>
       
    <svg preserveAspectRatio="xMidYMid slice" viewBox="10 10 80 80">
        <defs>
          
        </defs>
        <path fill="#B08BBB" class="out-top" d="M37-5C25.1-14.7,5.7-19.1-9.2-10-28.5,1.8-32.7,31.1-19.8,49c15.5,21.5,52.6,22,67.2,2.3C59.4,35,53.7,8.5,37-5Z"/>
    
        <path fill="#FFC436" class="out-bottom" d="M105.9,48.6c-12.4-8.2-29.3-4.8-39.4.8-23.4,12.8-37.7,51.9-19.1,74.1s63.9,15.3,76-5.6c7.6-13.3,1.8-31.1-2.3-43.8C117.6,63.3,114.7,54.3,105.9,48.6Z"/>
    
    </svg>
    
    
   
    <div id="containerAbout"> 
        <div id="logo">
        <img src="../assets/logoPB.png" alt="logoPB">

    </div>
        <div id="containerTexto">
            <h1>TITULO TIT </h1>
            <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, <br> Duis aute irure dolor in reprehenderit  </p>
            
        </div>
        <div id="containerImg">
<img src="../assets/pastaMani.png" alt="pastaMani">
        </div>

    </div>
  
    </section>
   
</template>
<style scoped>
@keyframes rotate {
                         0% {
                        transform: rotate(0deg);
                    }
                    100% {
                        transform: rotate(360deg);
                    }
                }
                .out-top {
                    animation: rotate 20s linear infinite;
                    transform-origin: 13px 25px;
                }
                .in-top {
                    animation: rotate 10s linear infinite;
                    transform-origin: 13px 25px;
                }
                .out-bottom {
                    animation: rotate 25s linear infinite;
                    transform-origin: 84px 93px;
                }
                .in-bottom {
                    animation: rotate 15s linear infinite;
                    transform-origin: 84px 93px;
                }
body {
    background-color: #F0EDD4;
}
svg {
    position: relative;
    top: 0;
    right: 0;
    width: 100%;
    height: 100vh;
 
}
#containerTexto{
    position: absolute;
    left: 60px;
    top: 30%;
}
h1{
    position: relative;
    color:#232323 ;
    font-size: 120px;
    margin-bottom: 0;
}
p{ position: relative;
    color: #232323;
    font-size: 35px;
    width: 750px;
}
#containerImg{position: absolute;
left: 40%;
top: 15px;}
#containerImg img{width: 1000px;
}
#logo{position: absolute;
left: 5%;
right: 0;
top:50px;
width: 150px;

}



</style>