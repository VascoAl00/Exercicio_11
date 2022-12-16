<script>
  
  document.getElementById("BtnPurple").onclick = changeColorPurple;
  document.getElementById("BtnGreen").onclick = changeColorGreen;
  document.getElementById("BtnOrange").onclick = changeColorOrange;
  document.getElementById("BtnGold").onclick = changeColorGold;
  document.getElementById("BtnBoring").onclick = changeColorDefault;

  function changeColorPurple(){

    document.getElementById("main").classList.add("purple");
    document.getElementById("main").classList.remove("orange, nocolor, green, gold");

  }

  function changeColorGreen(){

    document.getElementById("main").classList.add("green");
    document.getElementById("main").classList.remove("orange, nocolor, purple, gold");

  }

  function changeColorOrange(){

    document.getElementById("main").classList.add("orange");
    document.getElementById("main").classList.remove("purple, nocolor, green, gold");

  }

  function changeColorGold(){

    document.getElementById("main").classList.add("gold");
    document.getElementById("main").classList.remove("orange, nocolor, green, purple");

  }

  function changeColorDefault(){

    document.getElementById("main").classList.add("nocolor");
    document.getElementById("main").classList.remove("orange, purple, green, gold");

  }

</script>

<main class ="nocolor">

  <div>

    <h1>Eu gosto muito de...</h1>

  </div>

  <div>

    <div>

      <button type="button" id="BtnPurple" >Roxo</button>

    </div>

    <div>

      <button type="button" id="BtnOrange">Laranja</button>

    </div>

    <div>

      <button type="button" id="BtnGreen">Verde</button>

    </div>

    <div>

      <button type="button" id="BtnGold">Dourado</button>

    </div>

    <div>

      <button type="button" id="BtnBoring">O meu gosto está errado :/</button>

    </div>

  </div>
    



</main>

<style>
#main {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vw;
}

.nocolor{

background-color: #ffffff;
transition: background-color 2s ease-out;

}

.purple{

background-color: #8500EE;
transition: background-color 2s ease-out;

}

.orange{

background-color: #FF9700;
transition: background-color 2s ease-out;

}

.green{

background-color: #17FF00;
transition: background-color 2s ease-out;

}

.gold{

background-image: url("https://img.freepik.com/premium-photo/shiny-yellow-leaf-gold-foil_38679-857.jpg?w=2000");
background-color: #F3D604;
transition: background-color 2s ease-out;

}

</style>
