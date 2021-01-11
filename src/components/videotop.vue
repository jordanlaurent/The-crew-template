<template>
<div >
   <nav class="navbar navbar-expand-lg  navColor">
  <img src="../assets/img/The_Crew_2_Logo.png" alt="logo the crew 2">
  <button class="navbar-toggler navbar-dark" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse navbar-dark navposition" id="navbarNav">
    <ul class="navbar-nav fontnav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Acceuil <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#informations">Informations</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#disponibles">Disponible</a>
      </li>
      <li class="nav-item">
        <a class="nav-link " href="#contact">Contact</a>
      </li>
    </ul>
  </div>
</nav>
<video autoplay muted loop id="bgvid" >
  <!-- <source src="../assets/Beach.webm" type="video/webm"> -->
  <source src="../assets/video/trailer-the-crew.mp4" type="video/mp4"> </video>
</div>
</template>
<style lang="css">
video#bgvid { min-width: 100%; max-width: 100%; position:relative; top:0;}
.navColor{background-color: #0F0F10; position: fixed;top: 0;}
.navposition{display: flex;justify-content: space-evenly;}
@media (min-width: 860px) {
.fontnav{font-size:2vw} }
</style>