<script setup>
import { ref } from 'vue';
import { onMounted, onBeforeMount } from 'vue';
import Hero from './components/Hero.vue';
import ToDoItem from './components/moz-todo-vue/ToDoItem.vue';
import heroSection from './components/etalon-vue/hero/heroSection.vue';
import brandBar from './components/etalon-vue/brand-bar/brandBar.vue';
import bestSellers from './components/etalon-vue/best-sellers/bestSellers.vue';
import Collections from './components/etalon-vue/collections/collections.vue';
import footerSection from './components/etalon-vue/footer/footerSection.vue';
import Test from './components/test/test.vue';
const message = "get Free";
const name = ref('')
onBeforeMount(()=>{
  console.log('test: before mount');
  
})
onMounted(()=>{
  console.log('test: on mounted');
  
})
</script>

<template>
<!-- HI , {{ message }} -->

<!-- 
  <input v-model="name" type="text">
  <div>{{ name }}</div> -->
<!-- <heroSection/>  
<brandBar/>
<Collections/>
<bestSellers/>
<footerSection/> -->
<Test/>


</template>

