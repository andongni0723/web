<script setup>
import RightArrowIcon from "@/Icon/RightArrow-Icon.vue";
</script>

<template>
<div class="project-show">
  <div class="project">
    <div class="index">
      <h1 class="title">01</h1>
    </div>
    <div class="details">
      <img class="detail-img" src="@/assets/main-view-img/crossing.jpeg" alt="" >
      <div class="name-and-button">
        <h1 class="title size4">Crossing</h1>
        <!--<font-awesome-icon icon="fa-solid fa-arrow-right" style="color: #ffffff;" />-->
        <div class="go-button">
          <p class="button-text">查看</p>
          <i class="fa-thin fa-arrow-right-long"></i>
        </div>
      </div>
    </div>
  </div>
  <hr class="line">
</div>
</template>

<style scoped>
.project-show {
  background-color: var(--main-drak-black-color);
}

.project{
  padding: 30px 0;
  min-width: auto;
  display: flex;
  gap: 80px;

}

.index {
  margin-left: max(0px, calc((100% - 980px) * 0.5));
}

.title {
  font-family: "Impact","JetBrains Mono NL",serif;
  color: var(--main-white-color);
  font-size: 3rem;
}

.size4 {
  font-size: 4rem;
}

.details {
  width: 100%;
  overflow: hidden;
}

.detail-img {
  object-fit: cover;
  width: 1122px;
  height: 632px;
  border-radius: 20px 0 0 20px;
}

.name-and-button {
  display: flex;
  align-items: center;
  padding: 30px 50px;
}

.go-button {
  border: var(--main-light-black-color) solid 1px;
  border-radius: 30px;
  color: var(--main-white-color);
  width: 100px;
  margin: 30px 50px;
  padding: 15px 15px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  transition: 0.2s;
  font-weight: bold;
  font-size: 0.9rem;
  letter-spacing: 0.2rem;
}

.go-button:hover {
  background-color: var(--main-white-color);
  color: var(--main-light-black-color);

}

.button-text {

}

</style>
