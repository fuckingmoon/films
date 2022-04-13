<template>
  <div class="d"> 
      <h2>Fury</h2> 
      <div> 
          
          <img src="./foto/furyfoto.jpg" alt="">
      <p>Fury is a 2014 American war film written and directed by David Ayer, and starring Brad Pitt, Shia LaBeouf, Logan Lerman, Michael Peña, Jon Bernthal, Jason Isaacs and Scott Eastwood. The film portrays US tank crews fighting in Germany during the final weeks of the European theater of World War II. Ayer was influenced by the service of veterans in his family and by reading books such as Belton Y. Cooper's Death Traps, about American armored units in World War II and the high casualty rates suffered by tank crews in Europe.
Production began in early September 2013, in Hertfordshire, England, followed by principal photography on September 30, 2013, in Oxfordshire. Filming continued for a month-and-a-half at different locations, which included the city of Oxford, and concluded on November 13. Fury was released on October 17, 2014, received positive reviews, and grossed $211 million worldwide.</p>
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
    background: url(./foto/furyfon.jpg);
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
    color: black;
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