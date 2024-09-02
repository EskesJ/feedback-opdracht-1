<script>
  export default {
    name: 'HelloWorld'
  }
</script>

<template>
  <header>
    <div id="inner-header-wrapper">
      <img id="logo" src="../assets/RealEstateCare logo.png" alt="logo van RealEstateCare">
      <div id="h1-wrapper">
        <h1>Real Estate Care</h1>
        <p>Caring is in our nature</p>
      </div>
    </div>
    <div class="circle circle-1"></div>
    <div class="circle circle-2"></div>
  </header>
</template>

<style scoped>

  header {
    block-size: 130px;
    display: flex;
    align-items: center;
    overflow: hidden;
    position: relative;
  }

  #inner-header-wrapper {
    inline-size: 80%;
    margin-inline: auto;
    display: flex;
    justify-content: flex-start;
    align-items: center;
  }

   #logo {
    block-size: 80px;
    inline-size: 80px;
    margin-inline-end: 30px;
   }

   h1 {
    margin-block: 0px;
   }

   #h1-wrapper p {
    margin-block: 0px;
    font-weight: bold;
   }

   .circle {
    position: absolute;
    border-radius: 50%;
    block-size: 1000px;
    inline-size: 3000px;
   }

   .circle-1 {
    background-color: rgb(0, 170, 162);
    right: -1500px;
    top: 0px;
   }
   .circle-2 {
    background: rgb(71,94,108);
    background: linear-gradient(90deg, rgba(71,94,108,1) 0%, rgba(20,27,31,1) 50%);
    right: -1700px;
    top: 40px;
   }
</style>
