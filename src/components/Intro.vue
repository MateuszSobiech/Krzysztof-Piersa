<template>
  <div class="wrapperIntro">
    <h1>
      Krzysztof <br />
      Piersa
    </h1>
    <div class="opis">
      "Spokojnie, nie jestem natchnionym terapeutą krzyczącym wyłącz ten
      komputer i wyjdź na dwór. Dostaję ciarek za każdym razem jak słyszę coś
      takiego."
    </div>
  </div>
</template>

<script scoped>
export default {
  name: 'Intro'
}
</script>

<style>
.wrapperIntro {
  color: white;
  display: flex;
  flex-direction: column;
  position: absolute;
  top: 33%;
  left: 15%;
  margin-right: 60px;
}

@media (min-width: 768px) {
  .wrapperIntro {
    color: white;
    display: flex;
    font-size: 48px;
    flex-direction: column;
    position: absolute;
    top: 20%;
    left: 5%;
    margin: 0;
  }
  .wrapperIntro h1 {
    margin-bottom: 0;
  }
  .opis {
    margin-top: 20px;
    margin-left: 20px;
    width: 500px;
    font-size: 18px;
    line-height: 1.6;
  }
}
</style>