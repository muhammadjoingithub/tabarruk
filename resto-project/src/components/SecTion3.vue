<template>
      <section class="containeer-fluid section3">
        <div class="container many-countries">
         <center>
            <div class="countries-text">
                <h2>How many countries?</h2>
                <div class="slowdown-row"></div>
                <p>All countries that we represent</p>
            </div>
         </center>
            <div class="countries-hover">
                <div class="hover-columns">
                    <center>
                        <img src="../assets/images/turkiye2.png" alt="">
                    </center>
                    <h3>Türkiye</h3>
                    <p>27 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
                <div class="hover-columns">
                  <center>
                    <img src="../assets/images/uzbeks.png" alt="">
                  </center>
                    <h3>Uzbekistan</h3>
                    <p>32 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
                <div class="hover-columns">
                  <center>
                    <img src="../assets/images/turkmen2.png" alt="">
                  </center>
                    <h3>Turkmenistan</h3>
                    <p>24 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
                <div class="hover-columns">
                    <center>
                        <img src="../assets/images/azeri.png" alt="">
                    </center>
                    <h3>Azerbaijan</h3>
                    <p>12 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
                <div class="hover-columns">
                   <center>
                    <img src="../assets/images/hungary.png" alt="">
                   </center>
                    <h3>Hungary</h3>
                    <p>19 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
                <div class="hover-columns">
                    <center>
                        <img src="../assets/images/kazakhi.png" alt="">
                    </center>
                    <h3>Kazakhstan</h3>
                    <p>21 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
                <div class="hover-columns">
                    <center>
                        <img src="../assets/images/kyrgiz.png" alt="">
                    </center>
                    <h3>Kyrgyzstan</h3>
                    <p>9 destinations</p>
                    <div class="hover-rowbefore"></div>
                </div>
            </div>

        </div>

    </section>

</template>
<script>
export default {
  name: 'SecTion3'
}
</script>
<style>
.section3{
    background-color: rgb(8, 8, 8);
     height: auto;
}
.countries-text{
    padding: 30px;
}
.countries-text h2{
    color: var(--White, #FFF);
    font-feature-settings: 'liga' off, 'calt' off;
    text-shadow: 0px 10px 50px rgba(12, 15, 48, 0.40);
    font-family: "Playfair Display",serif;
    font-size: 40px;
    font-style: normal;
    font-weight: 600;
    line-height: 130%; /* 52px */
}
.slowdown-row{
    border-bottom: 2px solid #E54545;
    width: 100px;
}
.countries-text p{
    color: var(--White, #FFF);
    text-align: center;
    font-family: "Gilroy",sans-serif;
    font-size: 18px;
    font-style: normal;
    font-weight: 500;
    line-height: 130%; /* 26px */
    margin-top: 20px;
}
.countries-hover{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    gap: 20px;
    padding: 50px;
}
.hover-columns{
  width: 22%;
  
  padding:20px;
  border-radius: 12px;
  border: 1px solid rgba(255, 255, 255, 0.04);
  
}
.hover-columns:hover{
    cursor: pointer;
    border: 1px solid rgba(255, 255, 255, 0.04);
    background: rgba(255, 255, 255, 0.04);
    backdrop-filter: blur(15px);
    transition: all 0.3s ease-in-out ;
    transform: scale(1.1);
    
    .hover-rowbefore{
        background-color:blue;
        border-bottom: 2px solid grey;
        align-self: flex-end;
        display: flex;
    
    }
}
/* .hover-columns img{
    
} */
.hover-rowbefore{
    background-color:blue;
    border-bottom: 2px solid rgb(24, 23, 23);
   

}

.hover-columns h3{
    margin-top: 20px;
    color: var(--White, #FFF);
    text-align: center;
    font-family: "Gilroy",sans-serif;
    font-size: 20px;
    font-style: normal;
    font-weight: 600;
    line-height: 130%; /* 26px */
}
.hover-columns p{
    color: rgba(255, 255, 255, 0.60);
    text-align: center;
    font-family: "Gilroy",sans-serif;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 130%; /* 18.2px */
}
</style>
