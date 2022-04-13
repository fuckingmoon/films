<template>
  <div class="d"> 
      <h2>The Irishman</h2> 
      <div> 
          
          <img src="./foto/irishman2.jpg" alt="">
      <p>The Irishman (titled onscreen as I Heard You Paint Houses) is a 2019 American epic crime drama film directed and produced by Martin Scorsese and written by Steven Zaillian, based on the 2004 nonfiction book I Heard You Paint Houses by Charles Brandt. It stars Robert De Niro, Joe Pesci, and Al Pacino, with Ray Romano, Bobby Cannavale, Anna Paquin, Stephen Graham, and Harvey Keitel in supporting roles. The film follows Frank Sheeran (De Niro), a truck driver who becomes a hitman involved with mobster Russell Bufalino (Pesci) and his crime family, including his time working for the powerful Teamster Jimmy Hoffa (Pacino). The film marks the ninth collaboration between director Scorsese and De Niro, the first one between Scorsese and Pacino, and the fourth film in which both De Niro and Pacino appear in starring roles (after The Godfather Part II, Heat, and Righteous Kill).</p>
      </div>
      <ul>
          <li><a href="#">IMDB: 7.8</a></li>
          <li><a href="#">KinoPoisk: 7.4</a></li>
          
      </ul>
    
  </div>
</template>

<script>

</script>

<style scoped>
.d{
    background: url(./foto/theirishman.jpg);
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
    margin-top: 30px; 
}

p{
    width: 500px;
    text-align: center;
    color: white;
    font-size: 20px;
     margin-top: 30px; 
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