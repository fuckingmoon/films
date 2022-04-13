<template>
  <div class="d">  
     <h1>Movies this week</h1>
     <h2>Detechment</h2>
      <div> 
          
          <img src="https://avatars.mds.yandex.net/get-zen_doc/1904579/pub_5d90485cfc69ab00adca4ab4_5d904f15b477bf00b10863d2/scale_1200" alt="">
      <p>Detachment is a 2011 American drama film directed by Tony Kaye and distributed by Tribeca Film. It was written by Carl Lund. Its story follows Henry Barthes, a high-school substitute teacher who becomes a role model to his students and others. It stars Adrien Brody, Marcia Gay Harden, Christina Hendricks, William Petersen, Bryan Cranston, Tim Blake Nelson, Betty Kaye, Sami Gayle, Lucy Liu, Blythe Danner, and James Caan.
The film was produced by Greg Shapiro, Carl Lund, Bingo Gubelmann, Austin Stark, Benji Kohn, and Chris Papavasiliou and was released on March 16, 2012. It grossed $10,739 during its opening weekend and $1.68 million worldwide.[2] It received mixed reviews and has a 57% approval rating based on 72 reviews on Rotten Tomatoes.[3]</p>
      </div>
      <ul>
          <li><a href="#">IMDB: 7.7</a></li>
          <li><a href="#">KinoPoisk: 7.8</a></li>
          
      </ul>
    
  </div>
</template>

<script>

</script>

<style scoped>
.d{
    background: url(./foto/dechfon.jpg);
    width: 100%;

   height: 800px;
    /* background-position: center; */
    flex-wrap: wrap;
    background-size:cover ;
    flex-direction: column; 
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
}

p{
    width: 500px;
    text-align: center;
    color: white;
    font-size: 20px;
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

h1{
    margin: 0 auto;
    margin-top: 50px;
    font-size: 60px;
    
}
h2{
    font-size: 50px;
    color: rgb(255, 166, 1) ;
;
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