
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | 3-column preview card component</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  
</head>




<body>




  <section class="container">
    
    <div id="sed" class="logo1">
      <img src="images/icon-sedans.svg">
      <h1>SEDANS</h1>
      <p>Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city 
      or on your next road trip.</p> 
      <a href="">Learn More</a>
   </div>


    <div id="suv" class="logo1">
      <img src="images/icon-suvs.svg">
     <h1>SUVS</h1>
     <p>Take an SUV for its spacious interior, power, and versatility. Perfect for your next family vacation 
      and off-road adventures.</p>
     <a href="">Learn More</a>
   </div>

    <div id="lux" class="logo1"> <img src="images/icon-luxury.svg">
      <h1>LUXURY</h1>
     <p>Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury 
     rental and arrive in style.</p>
      <a href="">Learn More</a>
    </div>
    
  
  </section>
  




  <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Afrochamploo</a>.
    </div>


</body>
</html>



<style>

  body{
    background-color: rgb(255, 255, 255);
    font-family: lexend deca;
    font-size: 15px;
    line-height:1.7 ;
  }

  .container{
    display: flex;
    min-height: 500px;
    margin-top: 200px;
    color: rgb(255, 253, 253);
    
  }

  .logo1{
    background-color:hsl(31, 77%, 52%) ;
    align-items: center;
    width: 100%;
    padding-top: 50px;
    min-height: 500px;
    padding-left:30px;
    

  }

  .logo1 h1{
    padding-top: 10px;
    padding-bottom:30px;
    font-weight: 800;
    font-size: 30px;
  }

  #suv{
    background-color:hsl(184, 100%, 22%) ;

  }

  p{
    margin-bottom: 90px;
    font-weight: 400;
    
  }

  #lux{
    background-color:hsl(179, 100%, 13%) ;

  }

  .logo1 a{
    background-color: whitesmoke;
    padding:20px;
    border-radius: 40px;
    color:hsl(184, 100%, 22%);;
  }


  
  @media (max-width:700px) {
    .container{
      display: flex;
      flex-direction: column;
      margin-right:30px;
    }
  }














  .attribution { font-size: 11px; text-align: center; }
  .attribution a { color: hsl(0, 90%, 49%); }
</style>
