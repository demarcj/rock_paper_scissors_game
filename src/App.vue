<template>
  <div class="container">
    <TheHeader />
    <TheMain />
    <TheFooter />
  </div>
</template>

<script>
  import TheHeader from './components/TheHeader.vue';
  import TheMain from './components/TheMain.vue';
  import TheFooter from './components/TheFooter.vue';
  import "./style.css";

  export default {
    components: {
      TheHeader,
      TheMain,
      TheFooter
    }
  }
</script>

<style scoped>
  .container{
    max-width: 1600px;
    margin: 0 auto;
    padding: 0 15px;
  }
</style>
