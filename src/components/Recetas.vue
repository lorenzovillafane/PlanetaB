<template>
    <div id="recetasContainer">
        <div id="receta1">
            <img src="../assets/tarta.png" alt="TARTA">
<h3>TARTA VEGANA DE CHOCOLATE Y PASTA DE MANI</h3>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat molestias tenetur nostrum minus? Maiores voluptatem vitae perferendis omnis nulla in repellat officiis, rerum nisi porro qui, nesciunt distinctio modi inventore.</p>
        </div>
        <div id="receta2">
            <img src="../assets/alfajor.png" alt="ALFAJOR">
            <h3>ALFAJOR CHOCOLATE BLANCO Y MANI</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellat illo fugiat debitis reprehenderit architecto quibusdam officiis ad, voluptas exercitationem corrupti ea! Cupiditate in eligendi alias esse ea magni, autem consectetur!</p>
        </div>
        <div id="receta3">
            <img src="../assets/aro.png" alt="ARO DE MANZANA CON PASTA">
            <h3>ARITOS DE PASTA DE MANI</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Culpa reiciendis quo repellat, accusamus nulla nobis eos est optio voluptatibus, modi in provident quasi voluptas tempora suscipit? Iusto molestiae temporibus vitae!</p>
        </div>
      
    </div>
</template>
<style scoped>
#recetasContainer{display: flex;
justify-content: space-around;
margin-top: 50px;
}

#receta1{display: flex;
    flex-direction: column;
    width: 400px;
    align-items: center;
    background-color: #B08BBB;
border-radius: 10%;}
  
    #receta2{display: flex;
    flex-direction: column;
    align-items: center;
    width: 400px;
    background-color: #B08BBB;
    border-radius: 10%;}
   
    #receta3{display: flex;
    flex-direction: column;
    border-radius: 10%;
    align-items: center;
    width: 400px;
    background-color: #B08BBB;}
    img{width: 200px;}
h3{
text-align: center;
align-items: center;}
</style>