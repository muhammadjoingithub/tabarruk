<template>
    <div class="head-contain">
      <div class="no-collecton">
      <div class="container-fluid for-foto">
        <div class="container nav-collection">
            <nav class="navbar">
                 <a class="logo-link" href="./index.html">
                    <div class="logo-header">
                        <img src="../assets/images/logosun.svg" alt="">
                        <div class="logo-texts">
                            <h3 class="text1">Tabarruk Ziyorat</h3>
                            <h5 class="text2">Supported by The Ministry of Culture and Tourism</h5>
                        </div>
                     </div>
                 </a>
                 <ul class="ul">
                    <a href="#"><li class="links-type">About us</li></a>
                    <a href="#"><li class="links-type">Countries
                    </li></a>
                    <a href="#"><li class="links-type dropdown">
                        <span>Religions</span>
                        <div class="dropdown-content new-dropdown">
                            <div class="religions-mapcontext">
                                <img src="../assets/images/islam.png" alt="">
                                <div class="religion-map">
                                     <h3>Islam</h3>
                                     <p>32 destinations</p>
                                </div>
                            </div>
                            <div class="religions-mapcontext">
                                <img src="../assets/images/christian.png" alt="">
                                <div class="religion-map">
                                     <h3>Christianity</h3>
                                     <p>24 destinations</p>
                                </div>
                            </div>
                            <div class="religions-mapcontext">
                                <img src="../assets/images/budda.png" alt="">
                                <div class="religion-map">
                                     <h3>Buddism</h3>
                                     <p>19 destinations</p>
                                </div>
                            </div>
                        </div>
                    </li></a>
                    <a href="#"><li class="links-type">Heritage map</li></a>
                    <a href="#"><li class="links-type">Help</li></a>
                    <div class="dropdown">
                        <span><img src="../assets/images/3c259ce0-aced-4379-916c-bc245ec098e3.svg" alt=""></span>
                        <div class="dropdown-content">
                        <p><img src="../assets/images/3c259ce0-aced-4379-916c-bc245ec098e3.svg" alt=""><span>English</span></p>
                        <p><img src="../assets/images/rusia.png" alt=""><span>Русский</span></p>
                        <p><img src="../assets/images/kazakh.png" alt=""><span>Казакща</span></p>
                        <p><img src="../assets/images/turkmen.png" alt=""><span>Türkmen</span></p>
                        <p><img src="../assets/images/kirgyz.png" alt=""><span>Қыргызча</span></p>
                        <p><img src="../assets/images/azerbayjan.png" alt=""><span>Azərbaycan</span></p>
                        <p><img src="../assets/images/uzbekistan.png" alt=""><span>O’zbekcha</span></p>
                        <p><img src="../assets/images/turkiye.png" alt=""><span>Türk</span></p>
                        <p><img src="../assets/images/madyar.png" alt=""><span>Magyar</span></p>
                      


                        </div>
                      </div>
      
                </ul>
                <div class="new-aligntype">
                                 <form action="">
                        <input class="search-box" type="text">
                      <div><a href="#" class="city-list"></a></div>
                      
                      </form>
                      
                       <img class="search" src="../assets/images/search.svg" alt="">
                       <img class="xmark" src="../assets/images/Main/xmark-large.png" alt="">
                       
                      
                </div>
            
                 <img src="../assets/images/menu.png" alt="" class="menu">
            </nav>
                
    
            <!-- center section -->
            
                <div class="info-section">
               <center>
                <div class="inner-section">
                    <div class="info-facts1">
                        <img src="../assets/images/location.png" alt="">
                        <p class="info-p">Samarkand, Uzbekistan</p>
                    </div>
                    <h1 class="info-facts2">registan square</h1>
                    <p class="info-facts3">Stunning showcase of Islamic architecture in Samarkand, Uzbekistan, with three ornate madrasas adorned in blue tiles and calligraphic inscriptions, dating back to the 15th century.</p>
                    
                    <a class="global other-button1" href="#">
                        <p>Explore</p>
                        <img src="../assets/images/rightarrow.png" alt="">
                       </a>
                   
                 </div>
               </center>
                </div>


                <!-- carusel slider wripper -->
             
                <!-- carusel slider wripper -->
            
        </div>
      </div>
      </div>
    </div>
</template>
<script>
export default {
  name: 'NavBar'
}

</script>
<style >
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100&family=Space+Mono&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
}
.body{
  background-color: rgb(8, 8, 8);
}
.search-box{
  display: none;
  transition: all  0.3s ease-in-out;
  width: 400px;
  border-radius: 8px;
border: 1px solid rgba(255, 255, 255, 0.20);
background: rgba(255, 255, 255, 0.10);
backdrop-filter: blur(20px);
color: white;
outline: none;
border: none;
padding: 5px;
padding-left: 20px;
}
.new-aligntype{
  display: flex;
  gap: 20px;
  align-items: center;
}
.city-list{
  text-decoration: none;
}
.ul{
  margin-top: 15px;
margin-left: 30px;
}
.xmark{
  display: none;
  object-fit: cover;

}
.search-box:hover{
  cursor: pointer;
}

.head-contain{
    background-image: url(../assets/images/headerpng.png);
    height: 100vh;     
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
   
    
}
.logo-link{
  text-decoration: none;
  color: white;
}
.menu{
  display: none;
}
.links-type{
  color: var(--White, #FFF);
font-family: "Gilroy",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 130%; /* 20.8px */
}
.logo-link:hover{
  text-decoration: none;
  color: white;
  cursor: pointer;
  
}
.dropdown {   
    position: relative;
    display: inline-block;
    padding: 20px;
  }
  
  .dropdown-content {
    margin-top: 20px;
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    padding: 12px 16px;
    z-index: 1;
    border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.20);
background: rgba(255, 255, 255, 0.04);
backdrop-filter: blur(15px);

grid-template-columns: 1fr 1fr 1fr;
  }
  .dropdown-content p span{
    margin-left: 10px;
  }
  .religions-mapcontext{
    display: flex;
    align-items: center;
    gap: 20px;
   
  }
  .new-dropdown{
    width: 200px;
   
  }
  .religion-map{
    margin-top: 10px
  }
  .religion-map h3{
    color: var(--White, #FFF);
font-family: "Gilroy",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 500;
line-height: 130%; /* 20.8px */
margin-top: 0px;

  }
.religion-map p{
    color: rgba(182, 172, 172, 0.6);
font-family: "Gilroy",sans-serif;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: 130%; /* 18.2px */
margin-top: -2px;
  }
  .dropdown:hover .dropdown-content {
    display: block;
  }

  .navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .no-collecton{
    width: 100%;
    height: 100vh;
    background: linear-gradient(180deg, #07091C -4.12%, rgba(7, 9, 28, 0.60) 49.39%, rgba(7, 9, 28, 0.20) 85.78%, #07091C 100%);
    
  }
  .nav-collection{
    color: white;
    padding-top: 20px;

  }
  .for-foto{
    background-image: url(../assets/images/vector1.png);
    background-repeat: no-repeat;
  }
  .logo-header{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .ul{
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .ul a{
    text-decoration: none;
    color: white;
    padding: 10px;
  }
  .ul a:hover{
    text-decoration: none;
    color: #f7f3f3;
   
  }
  .logo-header{
    gap: 10px;
  }
.text1{
    text-transform: uppercase;
    font-size: 27px;
    margin-top: 5px;
}
.text2{
    font-size: 14px;
    margin-top: -5px;
}
.dropdown img{
    border-radius: 50%;

}
.dropdown span{
 
    width: 200px;
}
.search{
    padding: 20px;
}
.info-section{
    display: flex;
    justify-content: center;
    margin-top: 60px;
    align-items: center;
}

.info-p{
    margin-top: 15px;
}
.info-facts1{
    justify-self: center;
    /* background-color: red; */
    /* width: 300px; */
    display: flex;
    gap: 10px;
    align-items: center;
    justify-content: center;

font-family: "Gilroy",sans-serif;
font-size: 20px;
font-style: normal;
font-weight: 500;
line-height: 130%; /* 26px */
}
.info-facts2{
font-feature-settings: 'liga' off, 'calt' off;
text-shadow: 0px 10px 50px rgba(12, 15, 48, 0.40);
font-family: "Playfair Display",serif;
font-size: 80px;
font-style: normal;
font-weight: 700;
line-height: 130%; /* 104px */
text-transform: capitalize;
}
.info-facts3{
    width: 63%;

text-align: center;
font-family: "Gilroy",sans-serif;
font-size: 20px;
font-style: normal;
font-weight: 500;
line-height: 130%; /* 26px */
}
.info-facts4{
    width:15% ;
    height: auto;
    display: flex;
/* padding: 20px; */
align-items: center;
gap: 4px;
font-size: 20px;
border-radius: 8px;
background:  #E54545;
padding-left: 40px;

}
.info-facts4 p{
    margin-top: 14px;
 
font-family: "Gilroy",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 600;
line-height: 150%; /* 24px */
}
.info-facts6{
    text-decoration: none;
color: white;
}
.rightarrow{
    object-fit: cover;
    font-size: 9px;
}
.info-facts4{
  background-color: #d32727;
  cursor: pointer;
 
}
</style>
