<template>
<!-- 
här vill vi iterera över våra listor med kort
för varje kort skall vi ta med datan och rendera
en kort-komponent  -->
<main>
    <!-- //<v-for></v-for> -->
</main>
</template>

<script>
export default {
  name: "CardsContainer",
  data: {
    smallCards: [
      {
        id: 1,
        name: "Astronaut",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      },{
        id: 2,
        name: "Ninja",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      },{
        id: 3,
        name: "Nerd",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      },{
        id: 4,
        name: "Läkare",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      },{
        id: 5,
        name: "Gitarrknäppare",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      },
    ],
    largeCards: [{
        id: 11,
        name: "Astronaut",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      },{
        id: 12,
        name: "Astronaut",
        lorem:
          "Marfa artisan pok pok, coloring book shaman intelligentsia meh kinfolk affogato raw denim direct trade subway tile kombucha.",
      }],
  },
};
</script>

<style>
</style>