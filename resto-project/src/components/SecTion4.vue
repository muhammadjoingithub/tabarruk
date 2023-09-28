<template>
     <section class="containerr-fluid section4">
          <div class="container religions-section">
            <center>
                <div class="countries-text">
                    <h2>Religions</h2>
                    <div class="slowdown-row"></div>
                    <p>This website is created to share information about historical, unique places located in Turkic countries. </p>
                </div>
             </center>
             <div class="reilions-items">
                <div class="religion-box">
                    <img class="box-img" src="../assets/images/islamic.png" alt="">
                    <h2>ISLAM</h2>
                    <p>This website is created to share information about historical, unique places located in Turkic countries. </p>
                    <a href="#">See more<img src="../assets/images/rightarrow2.png" alt=""></a>
                </div>
                <div class="religion-box">
                    <img class="box-img" src="../assets/images/christianit.png" alt="">
                    <h2>CHRISTIANITY</h2>
                    <p>This website is created to share information about historical, unique places located in Turkic countries. </p>
                    <a href="#">See more<img src="../assets/images/rightarrow2.png" alt=""></a>
                </div>
                <div class="religion-box">
                    <img class="box-img" src="../assets/images/buddist.png" alt="">
                    <h2>BUDDISM</h2>
                    <p>This website is created to share information about historical, unique places located in Turkic countries. </p>
                    <a href="#">See more<img src="../assets/images/rightarrow2.png" alt=""></a>
                </div>
             </div>
 
          </div>
    </section>

</template>
<script>
export default {
  name: 'SecTion4'
}
</script>
<style>
.section4{
    background-color: rgb(8, 8, 8);
     height: auto;
}
.reilions-items{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 30px;
    padding: 20px;
}
.religion-box{
    width: 30%;
    padding: 30px;
    border-radius: 12px;
    border: 1px solid rgba(255, 255, 255, 0.20); 
}
.religion-box:hover{
    border-radius: 12px;
border: 1px solid rgba(255, 255, 255, 0.04);
background: rgba(255, 255, 255, 0.04);
backdrop-filter: blur(15px);
transition: all 0.2s ease-in-out;
cursor: pointer;
transform: scale(1.1);
.religion-box a:hover{
    color: #E54545;
    text-decoration: none;
}
    .box-img{
    background: var(--Main, #E54545);
    transition: all 0.2s ease-in-out;
    }
  
}
.box-img{
    padding: 4px;
    border-radius: 8px;
    border: 1px solid rgba(255, 255, 255, 0.20); 
}

.religion-box h2{
    color: var(--White, #FFF);
    font-family: "Gilroy",sans-serif;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 130%; /* 31.2px */
    margin-top: 20px;

}
.religion-box p{
    color: rgba(255, 255, 255, 0.60);
    font-family: "Gilroy",sans-serif;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: 130%; /* 20.8px */
    margin-top: 25px;
}
.religion-box a{
    color: #E54545;
    font-family: "Gilroy",sans-serif;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 130%; /* 20.8px */
    text-decoration: none;
}
</style>
