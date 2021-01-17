<template>
  <main>
    <button id="test" @click="test">Test</button>
  </main>
</template>
<script>
export default {
  methods:{
    test(){
      alert(`something`);
    }
  }
}
</script>
<style scoped>
  #test{    
    background: white;
    color:var(--button_text_color);
    border: 0;
    cursor: pointer;
  }
</style>