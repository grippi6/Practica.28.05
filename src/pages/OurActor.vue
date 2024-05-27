<template>
  <TheHeader></TheHeader>
  <div class="content-actor">
    <div class="carts">
      <div class="carts-actors" v-for="(actor, index) in actors" :key="index">
        <img :src="actor.image" :alt="actor.name">
        <p>{{ actor.name }}</p>
        <h3>{{ actor.role }}</h3>
        <h5>{{ actor.description }}</h5>
      </div>
    </div>
  </div>
</template>


<script setup>
import TheHeader from "@/components/TheHeader.vue";
import actorsData from "/src/data/actor.json"; // Assuming 'actors.json' is in your 'assets' folder

const actors = actorsData;

</script>

<style scoped>
.content-actor {
  width: 100%;
  height: 1320px;
  background-size: 100% 100%;
  padding: 20px;
  box-sizing: border-box;
  //background: url("../assets/image/постер.jpg") no-repeat;
}

.carts {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  padding: 20px;
  row-gap: 5%;
  column-gap: 5%;
}
.carts-actors p{
  font-family: Nyasha;
}
.carts-actors {
  text-align: center;
  background: white;
  border-radius: 13px;
  border: white solid 10px;
}

.carts-actors img {
  width: 100%;
  max-height: 180px;
  object-fit: cover;
  border-radius: 10px;
  margin-bottom: 10px;
}

</style>

