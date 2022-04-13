<template>
  <div class="d"> 
      <h2>Stringer</h2> 
      <div> 
          
          <img src="./././foto/stinger.jpg" alt="">
      <p>«Стрингер» (англ. Nightcrawler"Stringer" (eng. Nightcrawler - "Night hunter" or "Worm" [4] [5]) - American thriller filmed by director and screenwriter Dan Gilroy. The film was first screened at the Toronto Film Festival[6] and was released on October 31, 2014[1]. The lead role was played by Jake Gyllenhaal, who won a number of awards for her (including nominations for the British Academy BAFTA, the American Screen Actors Guild and the Hollywood Foreign Press Association Golden Globe awards) and unexpectedly remained without a second Academy Award nomination "Oscar" in the category "Best Actor"[7]. Director and screenwriter Dan Gilroy was nominated for an Oscar in the Best Original Screenplay category.</p>
      </div>
      <ul>
          <li><a href="#">IMDB: 7.9</a></li>
          <li><a href="#">KinoPoisk: 7.4</a></li>
          
      </ul>
    
  </div>
</template>

<script>

</script>

<style scoped>
.d{
    background: url(./foto/stringerfon.jpg);
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
    backdrop-filter: blur(30px);
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
    color:yellow;
    font-size: 60px;
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