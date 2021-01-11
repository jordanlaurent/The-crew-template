<template>
    <div id="informations">
        <section >
<img src="../assets/img/the-chase-crew.webp" alt="..." class="w-100">
        </section>
        <aside id="text">
  <h1 class="display-4">THE CREW 2</h1>
  <p class="lead">Bienvenue à Motornation, un gigantesque terrain de jeu en monde ouvert à l'image des USA, pensé pour les sports mécaniques et vous mettant aux commandes de voitures, motos, bateaux et avions.</p>
  <hr class="my-4">
  <p>Montrez de quoi vous êtes capable et devenez le meilleur pilote de tous les temps.</p>
        </aside>
    </div>
</template>
<style>
@media (min-width: 860px) {
#informations{display: flex;flex-direction: row;justify-content: space-around;padding-top: 5%;padding-bottom: 5%;} }
#text{ display: flex;flex-direction: column;justify-content: center; padding-right: 3%;padding-left: 3%; }
@media (max-width: 860px) {
#informations{display: flex; flex-direction: column-reverse;} }
h1{font-weight: bold;}
#informations{background-color:#fedc13;color:#040404;}
</style>