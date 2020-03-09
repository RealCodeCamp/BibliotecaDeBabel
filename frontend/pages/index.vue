<template>
  <div class="container">
    <h1>Biblioteca de Babel</h1>
    <upload />
  </div>
</template>
<script>
import upload from '../components/upload'

export default {
  components: {
    upload
  }
}
</script>
<style>
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
</style>
