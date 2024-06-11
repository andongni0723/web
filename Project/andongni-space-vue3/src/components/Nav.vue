<script setup lang="ts">
import Logo from '../logo/AndongniGame-Icon.vue';
import FacebookIcon from "@/logo/Facebook-Icon.vue";
import BiliBiliIcon from "@/logo/BiliBili-Icon.vue";
import GithubIcon from "@/logo/Github-Icon.vue";
</script>

<template>
<div class="nav">
  <div class="logo"><Logo/></div>
  <div class="right-side">
    <a class="nav-button" href="">ABOUT</a>
    <a class="nav-button" href="">PROJECTS</a>
    <FacebookIcon/>
    <BiliBiliIcon/>
    <GithubIcon/>
  </div>
</div>
</template>

<style scoped>
.nav {
  position: sticky;
  margin: 0;
  top: 0;
  max-width: 100vw;
  height: 15vh;
  display: flex;
  background-color: black;
  justify-content: left;
  align-content: center;

  align-items: center;
  //padding-left: 20px;
  padding: 0 20px 0 20px;
}

h1 {
  margin: 0;
  padding: 0;
}

.logo {
  //margin-right: 50%;
  width: 50%;
}
.right-side {
  width: 50%;
  display: flex;
  justify-content: right;
  align-items: center;
  gap: 1rem;
}

.nav-button {
  font-family: "JetBrains Mono NL",serif;
  font-size: 1.3rem;
  font-weight: bold;
  //margin: 0 20px 0 20px;
  color: white;
  outline: none;
  text-decoration: none;
}
</style>
