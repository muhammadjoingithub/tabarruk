<template>
      <section class="container-fluid section7">
        <div class="container">
            <center>
                <div class="countries-text">
                    <h2 class="">Instagram</h2>
                    <div class="slowdown-row"></div>
                    <p class="">Stay up-to-date on the latest news and developments in the Turkic world.</p>
                </div>
             </center>
           
        </div>

        <div class="big-webkit">
            <div class="slider">
                <div class="slide-track">
                    <div class="slideshow-more">
                     <img src="../assets/images/stambul.png" alt=""> 
                    </div>
                    <div class="slideshow-more">
                    <img src="../assets/images/stambul2.png" alt="">  
                    </div>
                    <div class="slideshow-more">
                     <img src="../assets/images/stambul.png" alt="">
                    </div>
                    <div class="slideshow-more">
                     <img src="../assets/images/stambul2.png" alt=""> 
                    </div>
                    <div class="slideshow-more">
                    <img src="../assets/images/stambul.png" alt="">
                    </div>
                    <div class="slideshow-more">
                   <img src="../assets/images/stambul2.png" alt="">
                    </div>
                     <div class="slideshow-more">
                     <img src="../assets/images/stambul.png" alt=""> 
                    </div>
                     <div class="slideshow-more">
                    <img src="../assets/images/stambul2.png" alt="">
                    </div>
                     <div class="slideshow-more">
                     <img src="../assets/images/stambul.png" alt="">
                    </div>
                  
                </div>
            </div>
        </div>
  </section>

</template>
<script>
export default {
  name: 'SecTion6'
}
</script>
<style>
.big-webkit{
    position: relative;
  
    display: flex;
    align-items: center;
    justify-content: center;
   
    
}
.slider{
    margin: auto;
   height: 500px;
    overflow: hidden;
    position: relative;
    width: 100%;

}
.slider .slide-track{
    -webkit-animation: scroll 30s linear infinite;
    animation: scroll 30s linear infinite ;
    display: flex;
    width: calc(250px * 14);
}
.slide-track{
    gap: 20px;
}
/* .slider .slideshow-more{
 
    /* width: 184px; */
 
.slideshow-more{
    display: flex;

/* padding: 12px 16px 12px 12px; */
padding: 4px ;
align-items: center;
gap: 16px;
flex-shrink: 0;
border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.10);
background: rgba(255, 255, 255, 0.10);
backdrop-filter: blur(15px);
cursor: pointer !important;
object-fit: cover !important;
transition: all 0.4s;
}
.slideshow-more img{
    border-radius: 5px;
   object-fit: cover;
height: 184px;

}
.capital1{
    color: rgba(255, 255, 255, 0.60);
font-family: "Gilroy",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 130%; /* 20.8px */
margin-top: 15px;
}
.capital2{
color: white;
font-family: "Gilroy",sans-serif;
font-size: 16px;
font-style: normal;
font-weight: 600;
line-height: 100%; /* 20.8px */
}
.new-carusel{
    width: 100%;
}
.slideshow-more:hover{
  
    transition: all 0.4s;
}
@-webkit-keyframes scroll{
    0%{
        transform: translateX(0) ;
    }
    100%{
        transform: translateX(calc(-250px * 7));
    }
}
@keyframes scroll{
     0%{
        transform: translateX(0) ;
    }
    100%{
        transform: translateX(calc(-250px * 7));
    }
}
</style>