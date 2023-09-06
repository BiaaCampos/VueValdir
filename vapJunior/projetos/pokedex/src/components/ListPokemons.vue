<script setup>
const pokemon = defineProps(["name", "url"]);
console.log(pokemon);
</script>

<template>
  <div class="col-4">
    <div class="card">
      <img class="card-img-top" src="https://assets.pokemon.com/assets/cms2/img/pokedex/detail/001.png" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">{{ pokemon.name }}</h5>
        <a :href="pokemon.url" target="_blank" class="btn btn-primary">aperta ai</a>
      </div>
    </div>
  </div>
</template>

<style></style>
