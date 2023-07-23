<template>
  <div>
      <section>
          <p>Section 1</p>
      </section>
      <section>
          <p>Section 2</p>
      </section>
      <section>
          <p>Section 3</p>
      </section>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss" scoped>
  @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
  $bg-light: #e3c0c0;
  $bg-dark: #817091;

  div{
    background-image:linear-gradient($bg-light, $bg-dark)
  }
  section{

      font-family: 'Press Start 2P', cursive;
      display: grid;
      place-items: center;
      align-content: center;
      min-height: 100vh;
  }
</style>