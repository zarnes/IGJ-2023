<template>
  <HelloWorld :sub-title="subTitle"></HelloWorld>

  <input type="text" v-model="subTitle">
</template>

<script setup>
import {ref} from 'vue';
//import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
import HelloWorld from '@/components/HelloWorld.vue';

const subTitle = ref("coucou je suis dynamique");
</script>

<style scoped>

</style>
