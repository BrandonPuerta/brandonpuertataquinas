<template>
  <div class="all">
      <div class="Date">

        <img class="photo" src="./assets/IMG_20211018_122858.jpg" alt="Photo">
        <div class="Dates">
          <h1 class="title1">ACERCA DE MÍ</h1>

          <p class="text1">Dispuesto a aprender día a día las nuevas tecnologías que ayuden a mejorar mis habilidades.</p>


          <h2 class="title1">DATOS DE CONTACTO</h2>

          <P class="text1">Celular: +57 315-844-6219</P>
          <p class="text1">Correo: brandonpuerta02@hotmail.com</p>
          <p class="text1">Direccion: Calle 18 # 5a-87, Colombia, Miranda-Cauca</p>
          <a class="text1">Github: </a>
          <a class="link" href="https://github.com/BrandonPuerta">https://github.com/BrandonPuerta</a>
        </div>
    </div>
    <div class="study">
      
      <div class="studies">
        <h1 class="name">BRANDON ALEXANDER PUERTA TAQUINAS</h1>
        <h3 class="subtitle1">PLUS</h3>

        <P>Conocimiento en Desarrollo de software, Desarrollo en aplicaciones web, lenguaje de Python, Nodejs, Vuejs.</p>


        <h3 class="subtitle2">EDUCACION</h3>

        <h4>Misión TIC (Universidad Tecnologica de Bolívar)</h4>

        <h5><a class="link1" href="https://drive.google.com/file/d/1LLeGE3d5xql89axDpnlWfTaimutS56-t/view?usp=share_link">Certificado MISIÓN TIC</a></h5>

        <h5>16/12/2022</h5>

        <ul>
          <li><a class="link1" href="https://drive.google.com/file/d/17aY10Ur6GJKUKQkmFdjcJkj5NhJyPcnc/view?usp=share_link">Fundamentos de Programacion en Lenguaje Python.</a></li>
          <li><a class="link1" href="https://drive.google.com/file/d/17lFhau_fgkHY6WhkUzHk4zQ1s0Ws4gh7/view?usp=share_link">Programación Básica en Lenguaje Java.</a></li>
          <li><a class="link1" href="https://drive.google.com/file/d/1LVVi_zafYM2Gajs1B0L2Djdxw_UkCg7F/view?usp=share_link">Desarrollo de Software.</a></li>
          <li><a class="link1" href="https://drive.google.com/file/d/1LXfuJHy_udbrLFm8S20j5VJNVganfphO/view?usp=share_link">Desarrollo de Aplicaciones Web.</a></li>
        </ul>

        <h4>Servicio Nacional de Aprendizaje - SENA</h4>

        <h5><a class="link1" href="https://drive.google.com/file/d/1IFCIx0iMgxwoii0OJe-z5kfOiczFxZnT/view?usp=share_link">Técnico de Sistemas</a></h5>
        <h5>17/12/2020</h5>

        <ul>
          <li>Mantenimineto de computadores preventico y predictivo.</li>
          <li>Ofimatica Basica.</li>
          <li>Introduccion al diseño de redes.</li>
        </ul>
      </div>

    </div>
  </div>
</template>

<script>
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  display: flex;
  justify-content: center;
  
}

.photo {
  border: solid;
  border-radius: 50%;
  width: 200px;
  height: 200px;

}

.study {
  color: rgb(50,62,79);
  background: rgb(245, 244, 244);
  float: left;
  text-align: center;
  width: 500px;
  padding-top: 75px;
  text-align: start;
}

.studies {
  padding: 0 20px 30px 40px;
  text-align: start;
  display: block;
  flex-wrap: wrap;
}

.Date {
  float: left;
  background: rgb(51,63,80);
  color: white;
  padding: 0;
  width: 350px;
  height: auto;
  padding-top: 100px;
  display: block;
  flex-wrap: wrap;
}

.all {
  width:auto;
  height: 850px;
  display: flex;
  justify-content: center;
  display: flex;
  flex-wrap: wrap;
}

.subtitle1, .subtitle2 {
  background: rgb(190,228,218);
  padding: 1px 2px 3px 4px;
  font-weight: 750;
}

.Dates {
  text-align: left;
  padding: 0 30px 30px 30px;
  width: 280px;
  height: 450px;
  margin: 10px 40px 30px 0;
}
.title1 {
  color: rgb(190,228,218);
}

.name {
  padding-bottom: 60px;
  font-weight: 700;
}

.link {
  color: white;
}

.link:hover {
  color: gray;
}

.link1 {
  color: black;
}

.link1:hover {
  color: gray;
}
</style>
