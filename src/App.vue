<script setup>

</script>


  <template>
    
    

    
    <nav class="navbar ">
  <div class="container-fluid">
    <a class="linkcor" href=""><h1 class="titulo">MVP Games</h1></a>
    </div>

    <div>
      <a  class="champions" href="#">CHAMPIONS</a>  <a  class="runes" href="#2">RUNES</a>  <a  class="rank"  href="#3">RANK</a>
      </div>


    <div>
    <form class="d-flex">
      <input class="pesquisa" type="search" placeholder="     SEARCH CHAMPIONS OR SUMMONER" aria-label="Search">
    </form>
  </div>
</nav>

<div class="retangle">
  <h2 class="winrate">Win Rate</h2>
  <div class="progress">
  <div class="progress-bar bg-success" style="width:65%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-success" style="width:59%"></div>
</div>
<p class="porce">51,90%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-success" style="width:48%"></div>
</div>
<p class="porce">51,89%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-success" style="width:30%"></div>
</div>
<p class="porce">51,84%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
  
</div>

<div class="retangle2">
  <h2 class="winrate">Ban Rate</h2>
  <div class="progress">
  <div class="progress-bar bg-danger" style="width:29%"></div>
</div>
<p class="porce">29,12%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
  <br>
  <div class="progress">
  <div class="progress-bar bg-danger" style="width:16%"></div>
</div>
<p class="porce">16,33%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-danger" style="width:14%"></div>
</div>
<p class="porce">14,62%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar bg-danger" style="width:13%"></div>
</div>
<p class="porce">13,46%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
  

</div>

<div class="retangle3">
  <h2 class="winrate">Pick Rate</h2>
  <div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
<br>
<div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
  <br>
  <div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
  <br>
  <div class="progress">
  <div class="progress-bar" style="width:100%"></div>
</div>
<p class="porce">52,33%</p>
<img  class="img" src="src/assets/Tahm_KenchSquare 1.png" alt="">
  
  
  

</div>



    
  </template>
 


   

<style scoped>
.img{
  filter: brightness(2.1);
  width: 10%;
  margin-left: 8.5%;
  margin-top: -18%;
  border-radius: 20%;
}
.porce{
  margin-left: 63%;
  margin-top: -6%;
  color: #000;
font-family: Farro;
font-size: 25px;
font-style: normal;
font-weight: 500;
line-height: normal;
}
.progress{
  width: 35%;
  height: 5%;
  margin-left: 23%;
  margin-top: 20%;
  
}

.winrate{
  margin-left: 3.5%;
  margin-top: 5%;
  color: #FFF;
text-align: center;
font-family: Manjari;
font-style: normal;
line-height: normal;
}
.retangle3{
  width: 500px;
height: 780px;
border-radius: 110px;
background: rgba(187, 210, 255, 0.12);
position: absolute;
margin-left: 1400px;
margin-top: 20px;
filter:contrast(5);
}
.retangle2{
  width: 500px;
height: 780px;
border-radius: 110px;
background: rgba(187, 210, 255, 0.12);
position: absolute;
margin-left: 738px;
margin-top: 20px;
filter:contrast(5);
}

.retangle{
  width: 500px;
height: 780px;
border-radius: 110px;
background: rgba(187, 210, 255, 0.12);
position: absolute;
margin-left: 50px;
margin-top: 20px;
filter:contrast(5);
}



.champions{
  margin-left: 100px;
  color: #000;
font-family: Marcellus SC;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;

}

.runes{
  margin-left: 10px;
  color: #000;
font-family: Marcellus SC;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;

}

.rank{
  margin-left: 20px;
  color: #000;
font-family: Marcellus SC;
font-size: 14px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;
}

.navbar{
  background: linear-gradient(180deg, #A4B2FF 0%, rgba(0, 41, 255, 0.20) 0.01%, rgba(0, 163, 255, 0.20) 47.4%, rgba(0, 240, 255, 0.10) 100%, rgba(0, 240, 255, 0.20) 100%);
    height: 150px;

}

.pesquisa{
  margin-right: 50%;
  margin-left: 2%;
  margin-bottom: 50px;
  border-radius: 10px;
  width: 1000px;
height: 35px;
align-items: center;
  
}
.linkcor{
  color: red;
  text-decoration: none;
}
.titulo{
  margin-left: 100px;
 margin-top: 20px;
  font-family: Marko One;
font-size: 40px;
font-style: normal;
font-weight: 400;
line-height: normal;
background: linear-gradient(180deg, #0A05FF 0%, #DB00FF 100%);
background-clip: text;
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}
</style>
