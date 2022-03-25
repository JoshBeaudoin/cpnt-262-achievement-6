<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
   <HelloWorld :msg= "person" />
</template>
<script setup>
import HelloWorld from '@/components/HelloWorld.vue' 
const person = "Batman"
</script>