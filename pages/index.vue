<script setup lang="ts">
const name = "Hello!"
function sayHello(): void {
  console.log(name)
}
</script>

<template>
  <h1>Hello Test</h1>
  <p>{{name}}</p>
  <button @click="sayHello">Say Hello</button>

</template>

<style scoped>

</style>