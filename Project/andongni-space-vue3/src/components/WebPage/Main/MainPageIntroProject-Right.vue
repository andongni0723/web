<script lang="ts" setup>
// import {RightArrowIcon} from "@/Icon/RightArrow-Icon.vue";
import { defineProps, computed } from 'vue';
import PageComponent from "@/components/WebPage/Main/MainPageIntroProject-Component.vue";

interface Props
{
  index: string;
  title: string;
  imgSrc: string;
  intro: string;
}

const props = defineProps<Props>();

const introFormat = props.intro;
// const imgSrcRequire : string = require(props.imgSrc);
</script>


<template>
  <PageComponent class="component" :index="index" :title="title" :imgSrc="imgSrc" :intro="introFormat"/>
</template>
