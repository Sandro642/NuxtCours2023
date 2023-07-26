<template>
  <div class="portfolio">
    <h1>{{ name }}</h1>
    <p>Âge : {{ age }}</p>
    <p>Métier souhaité : {{ profession }}</p>
    <p>Description :</p>
    <p>{{ description }}</p>
    <!-- Ajoutez d'autres informations à afficher ici -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "Votre Nom",
      age: 25,
      profession: "Développeur Web",
      description: "Je suis passionné par le développement web et j'aimerais partager mes projets avec le monde !",
      // Ajoutez d'autres données personnelles ici
    };
  },
};
</script>

<style>
.portfolio {
  /* Ajoutez des styles CSS personnalisés ici */
}
</style>
