<template>
    <div id="recetasContainer">
        <div id="receta1">
            <img src="../assets/tarta.png" alt="TARTA">
            <div id="contentReceta"><h3>TARTA VEGANA DE CHOCOLATE Y PASTA DE MANI</h3>
<ul>
    <h4>Para la corteza:</h4>
<li>1/2 Taza (60 GRAMO) avena</li>
<li>1/2 Taza (56 GRAMO) harina de almendra</li>
<li> 1/3 Taza (30 GRAMO) polvo de cacao</li>
<li>1/2 cucharilla extracto de vainilla o vainilla en polvo</li>
<li>4 cucharada miel de maple</li>
<li>1 cucharada leche de coco o más según sea necesario</li>
<h4>Para el relleno de mantequilla de maní:</h4>
<li>3/4 Taza (195 GRAMO) mantequilla de maní suave</li> 
<li>3/4 Taza (177.44 ml) Leche de coco entera</li>
<li>3 a 4 cucharada (40 GRAMO) Azúcar u otro endulzante de tu preferencia</li>
<li>1/2 cucharilla extracto de vainilla</li>
<h4>Para la cobertura de chocolate:</h4>
<li>1/4 Taza (45 GRAMO) chocolate vegano semidulce</li>
<li>1.5 cucharada leche de coco</li>
</ul>
            </div>
        </div>
        <div id="receta2">
            <img src="../assets/alfajor.png" alt="ALFAJOR">
            <div id="contentReceta"> <h3>ALFAJOR CHOCOLATE BLANCO Y MANI</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellat illo fugiat debitis reprehenderit architecto quibusdam officiis ad, voluptas exercitationem corrupti ea! Cupiditate in eligendi alias esse ea magni, autem consectetur!</p> </div>
           
        </div>
        <div id="receta3">
            <img src="../assets/aro.png" alt="ARO DE MANZANA CON PASTA">
            <div id="contentReceta">
                <h3>ARITOS DE PASTA DE MANI</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Culpa reiciendis quo repellat, accusamus nulla nobis eos est optio voluptatibus, modi in provident quasi voluptas tempora suscipit? Iusto molestiae temporibus vitae!</p>
            </div>
            
        </div>
      
    </div>
</template>
<style scoped>
#recetasContainer{display: flex;
justify-content: space-around;
margin-top: 80px;
}
#contentReceta{margin-top: 0;}
#receta1{display: flex;
    flex-direction: column;
    width: 400px;
    align-items: center;
    background-color: #B08BBB;
    padding: 15px;
border-radius: 30px}
#receta1 img{position: absolute;}
  
    #receta2{display: flex;
    flex-direction: column;
    align-items: center;
    width: 400px;
    background-color: #B08BBB;
    border-radius: 30px;
    height:75vh ;
    padding: 15px;}
    
    #receta2 img{position: absolute;}
    
    #receta3{display: flex;
    flex-direction: column;
    border-radius: 30px;
    align-items: center;
    width: 400px;
    background-color: #B08BBB;
    padding: 15px;}
    
    img{width: 200px;
       
    }
    #receta1 img{position:relative;
        top: -75px;
       
    }
    #receta2 img{position:relative;
        top: -75px;
    }
    #receta3 img{position:relative;
        top: -75px;
    }
h3{ font-size: 35px;
text-align: center;
margin: 0;
position: relative;
top: -25px;}
li{font-size: 20px;
list-style: none;}
h4{font-size: 22px;}

</style>