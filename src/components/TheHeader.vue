<template>
  <header>
    <section class="left_header">
      <h1>Rock,<br> Paper,<br> Scissoors</h1>
    </section>
    <section class="right_header">
      <h2 class="score">Score</h2>
      <p class="score_count">{{ score_count }}</p>
    </section>
  </header>
</template>


<script>
  export default {
    data(){
      return {
        score_count: 0
      }
    }    
  }
</script>
<style scoped>
  .right_header{ 
    background: white;
    text-align: center;
    border-radius:var(--rounded_corners);
  }
  .score{color:#2A46C0}    
  .score_count{color:var(--button_text_color);}
</style>