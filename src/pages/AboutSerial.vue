<script setup>
import TheHeader from "@/components/TheHeader.vue";

</script>

<template>
  <div>
    <TheHeader></TheHeader>
    <div class="content">
      <h1>О сериале "Кухня"</h1>
      <p>Российский комедийный ситком о закулисной жизни одного из столичных лакшери-ресторанов. Сага со звездным актерским составом об истории сотрудников одного московского ресторана высокой кухни. Заведение с громким названием «Клод Моне» славится на всю столицу своей изысканной кухней, от посетителей самого высокого ранга нет отбоя, а повара здесь самые настоящие небожители.</p>
      <p>«Ку́хня» — российский телесериал в жанре ситуационной комедии с элементами мелодрамы. Создан компаниями Yellow, Black and White и KeyStone Production по заказу телеканала «СТС». Сериал посвящён работе сотрудников элитного ресторана французской кухни «Claude Monet» (1—4 сезоны) и ресторана «Victor» (5—6 сезоны), находящегося внутри отеля «ELEON».</p>
      <p>Главные герои сериала - Юлия Варламова, Максим Дрозд, Анастасия Панина, Дмитрий Назаров, Сергей Лавыгин, Мария Голубкина и другие. Сюжет сериала полон юмора, интриг и неожиданных поворотов. "Кухня" завоевала популярность среди зрителей и стала одним из самых успешных российских комедийных сериалов.</p>
    </div>
  </div>
</template>

<style scoped>
.content {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
 font-family: Life;
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 10px;
}

p {
  font-size: 20px;
  line-height: 1.6;
}
</style>