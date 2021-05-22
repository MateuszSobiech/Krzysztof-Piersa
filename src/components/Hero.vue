<template>
  <div class="heroImg" />
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped>
.heroImg {
  width: 100%;
  min-height: 100vh;
  position: fixed;
  top: 0;
  background-image: url("../../img/hero.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 43% 50%;
  z-index: -1;
}
</style>