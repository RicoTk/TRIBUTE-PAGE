# TRIBUTE-PAGE

<!DOCTYPE html>
<html>

<style>
    header {
        
        display: flex;
        flex-direction: column;
       
    }
    
   
   h1{
       
       display:flex;
       justify-content: center;
   }
   h2{
      
       display:flex;
       justify-content: center;
   }
   div{
       display: flex;
       flex-direction: column;
       justify-content: center;
       padding-top: 30px;
   }

   .responsive-img{
       max-width: 100%;
       height: auto;
   }
  
   img{
       border-radius: 10%;
   }
   body{
       background-color: bisque;
       padding: 10%;
   }
    
   .caption {
       
       display:flex;
       justify-content: center;
       font-style: italic;
       padding: 10px 0px 10px 0px;
       
   }

   li{
       padding: 2px 0px 2px 0px;
   }


    .link-format{
       padding: 5px 0px 5px 0px;
       text-align: center;
    }

   .info-format{
       align-self: center;

   }
</style>

<header>

    <h1 id="title"> Dr. Bill Russell </h1>  
    <h2> An NBA legend </h2> 

</header>
<body id="main">

    <div id="img-div"><img id="image" class="responsive-img" src="http://res.cloudinary.com/ybmedia/image/upload/c_crop,h_2000,w_2000,x_0,y_0/c_scale,f_auto,q_auto,w_700/v1/m/7/c/7c4856500eb3c82638ef3d1b197ecd937d004b63/GettyImages-74072185.jpg" 
    alt="NBA legend Bill Russell with his rings"> <p class="caption" id="img-caption"> NBA legend Bill Russell with his rings </p>
</div>
  

    <p class="info-format"> 
        <ul>
            <li id="tribute-info" >William Felton Russell (born February 12, 1934) is an American former professional basketball player who played as a center for
     the Boston Celtics of the National Basketball Association (NBA) from 1956 to 1969.</li> 
            <li id="tribute-info">A five-time NBA Most Valuable Player and a 12-time All-Star, he was the centerpiece of the Celtics dynasty that won eleven NBA championships during his 13-year career.</li>
            <li id="tribute-info">Russell and Henri Richard of the National Hockey League are tied for the record of the most championships won by an athlete in a North American sports league.</li>
            <li id="tribute-info">Russell led the San Francisco Dons to two consecutive NCAA championships in 1955 and 1956, and he captained the gold-medal winning U.S. national basketball team at the 1956 Summer Olympics</li>
        </ul>
    </p>

    <p class="link-format">Read more about his great career <a target="_blank" id="tribute-link" href="https://pt.wikipedia.org/wiki/Bill_Russell">here</a> </p>
</body>
</html>
