<template>
  <div class="d"> 
      <h2> The Suicide Squad</h2> 
      <div> 
          
          <img src="./foto/suicidesquad.jpg" alt="">
      <p>The Suicide Squad is a 2021 American superhero film based on the DC Comics team Suicide Squad. Produced by DC Films, Atlas Entertainment, and The Safran Company, and distributed by Warner Bros. Pictures, it is a standalone sequel to Suicide Squad (2016) and the tenth film in the DC Extended Universe (DCEU). It was written and directed by James Gunn and stars an ensemble cast including Margot Robbie, Idris Elba, John Cena, Joel Kinnaman, Sylvester Stallone, Viola Davis, David Dastmalchian, Daniela Melchior, Michael Rooker, Jai Courtney, Peter Capaldi, Alice Braga, and Pete Davidson. In the film, several convicts join a task force known as the "Suicide Squad" in exchange for lighter sentences. They are sent to the island nation of Corto Maltese to destroy all traces of the giant alien starfish Starro the Conqueror before it falls into the local government's control.</p>
      </div>
      <ul>
          <li><a href="#">IMDB: 7.2</a></li>
          <li><a href="#">KinoPoisk: 6.2</a></li>
          
      </ul>
    
  </div>
</template>

<script>

</script>

<style scoped>
.d{
    background: url(./foto/suicidesquadfon.jpg);
    width: 100%;
   height: 800px;
   background-size: cover ;
    background-position: center;
    flex-wrap: wrap;
    flex-direction: column; 
    align-items: center;
    
}
div{
  width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}
img{
    display: block;
    width: 500px;
    margin: 30px 0; 
    margin-top: 80px; 
}

p{
    width: 500px;
    text-align: center;
    color: white;
    font-size: 20px;
     margin-top: 80px; 
}

ul{
    display: flex;
    margin: 0 auto;
    font-size: 30px;
    margin-bottom: 50px; 
    gap: 30px;  
}
a{
    color: rgb(255, 166, 1) ;
}
h2{
    margin-top: 100px;
    color: rgb(255, 166, 1);
    font-size: 40px;
}
@media (max-width:1250px) {
    p{
       display: none;
        
    }
    img{
        margin: 0 auto;
    }
    
}
@media (max-width:1250px) {
    p{
       display: none;
        
    }
    div{
        width: 100%;
    }
    img{
        margin: 0 auto;
        width: 100%;
    }
    .d{
        width: 100%;
    }
}
@media (max-width:450px) {
    img {
        /* height: 200px; */
        width: 200px;
    }
    div{
        width: 100%;
        
    }
    .d{
        height: 400px;
    }
    h1{
    
    font-size: 30px;
    
}
h2{
    font-size: 20px;
   
}
ul{
    font-size: 10px;
   
}
}

</style>