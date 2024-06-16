<script setup lang="ts">
import MainView from "@/components/MainView.vue";
import Nav from "@/components/Nav.vue";
import BigTitle from "@/components/BigTitle.vue";
import ProjectCrossing from "@/components/ProjectCrossing.vue";
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
</script>

<template>
  <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v6.4.2/css/all.css">
  <!--<link rel="stylesheet" href="/main.css">-->
  <Nav/>
  <MainView/>
  <BigTitle/>
  <ProjectCrossing/>
</template>

<style scoped>
</style>
