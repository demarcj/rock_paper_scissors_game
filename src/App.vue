<template>
  <div class="container">
    <ScoreBoard />
  </div>
</template>

<script>
  import ScoreBoard from './components/ScoreBoard.vue';
  import "./style.css";

  export default {
    name: 'App',
    components: {
      ScoreBoard
    }
  }
</script>

<style scoped>
  .container{
    max-width: 1600px;
    margin: 0 auto;
  }
</style>
