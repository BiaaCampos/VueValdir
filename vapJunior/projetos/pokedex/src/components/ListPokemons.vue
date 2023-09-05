<script setup>
const pokemon = defineProps(["name", "url"]);
console.log(pokemon);
</script>

<template>
  <div class="col-4">
    <div class="card mb-3">
      <p class="text-center">{{ pokemon.name }}</p>
      <img src="https://assets.pokemon.com/assets/cms2/img/pokedex/detail/001.png" alt="" class="card-img-top">
    </div>
    <div class="card" style="width: 18rem;">
      <img class="card-img-top" src="..." alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
          content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
    </div>
  </div>
</template>

<style></style>
