<template>
  <div class="person">
    <h2>this is a {{car.brand}}, it price is {{car.price}}w</h2>
    <button @click="changePrice">change car price</button>
    <br>
    <h2>game list: </h2>
    <ul>
      <li v-for="g in games" :key="g.id">{{g.name}}</li>
    </ul>
    <button @click="changeFirstGame">change first game name</button>
  </div>
</template>

<!--尚硅谷Vue3 p13 10:06-->
<script setup lang="ts" >
  import {ref} from "vue";
  defineOptions({name: 'Person123'})

  let car = ref({brand: 'andongni', price: 100})
  let games = ref([
    {id: "a0001", name: "DoCard:H"},
    {id: "z1924", name: "DoCard: CubeMixer"},
    {id: "ss1024", name: "GunShoot"}
  ])
  function changePrice(){
    car.value.price += 10
  }
  function changeFirstGame(){
    games.value[0].name = "LowerToTop"
  }
</script>

<style scoped>
</style>
