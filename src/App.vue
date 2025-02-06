<script setup>
  import tophead from './components/tophead.vue'
  import txt from './components/txt.vue'
  import write from './components/write.vue'
  import darkmode from './components/darkmode.vue'
</script>

<template>
  <tophead></tophead>
  <txt></txt>
  <write></write>
  <darkmode></darkmode>
</template>

<style scoped>
   *{
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins';
 }
</style>