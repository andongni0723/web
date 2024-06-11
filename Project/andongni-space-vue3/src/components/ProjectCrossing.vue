<script setup>

</script>

<template>
<div class="project-show">
  <div class="project">
    <div class="index">
      <h1 class="title">01</h1>
    </div>
    <div class="details">
      <img class="detail-img" src="@/assets/main-view-img/crossing.jpeg" alt="" >
      <h1 class="title">01</h1>
    </div>
  </div>
  <hr class="line">
</div>
</template>

<style scoped>
.project-show {
  background-color: black;
}

.project{
  padding: 50px 0 100px 150px;
  max-width: 100vw;
  display: flex;
  gap: 80px;

}

.title {
  font-family: "JetBrains Mono NL",serif;
  font-weight: bold;
  color: white;
  font-size: 3rem;
}

.details {
  //width: calc(100vw - 187.6px);
  width: 840px;
}

.detail-img {
  //overflow-x: hidden;
  //overflow-y: clip;
  overflow: hidden;
  object-fit: cover;
  width: 1122px;
  //width:500px;
  white-space: nowrap;
  height: 100%;

  overflow-clip-margin: content-box;
}
</style>
