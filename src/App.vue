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
      <input class="pesquisa" type="search" placeholder="SEARCH CHAMPIONS OR SUMMONER" aria-label="Search">
    </form>
  </div>
</nav>

    
  </template>
 


   

<style scoped>



.champions{
  margin-left: 100px;
  color: #000;
font-family: Marcellus SC;
font-size: 10px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;

}

.runes{
  margin-left: 60px;
  color: #000;
font-family: Marcellus SC;
font-size: 10px;
font-style: normal;
font-weight: 400;
line-height: normal;
text-decoration: none;

}

.rank{
  margin-left: 60px;
  color: #000;
font-family: Marcellus SC;
font-size: 10px;
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
  margin-left: 20%;
  margin-bottom: 50px;
  border-radius: 10px;
  width: 1000px;
height: 35px;
  
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
