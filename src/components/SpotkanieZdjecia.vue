<template>
  <div class="zdjeciaWrapper">
    <div class="row">
      <img
        class="zdjecia"
        src="../../img/spotkanie1.jpg"
        alt="spotkanie autorskie w bibliotece"
      />
      <img
        class="zdjecia"
        src="../../img/spotkanie2.jpg"
        alt="wywiad w telewizji"
      />
      <img
        class="zdjecia"
        src="../../img/spotkanie3.jpg"
        alt="spotkanie autorskie z dziećmi"
      />
    </div>
    <div class="row">
      <img
        class="zdjecia"
        src="../../img/spotkanie4.jpg"
        alt="wywiad w telewizji"
      />
      <img class="zdjecia" src="../../img/spotkanie5.jpg" alt="prelekcja TED" />
      <img
        class="zdjecia"
        src="../../img/spotkanie6.png"
        alt="Krzysztof i Kosmiczny Bóbr"
      />
    </div>
    <div class="row">
      <img
        class="zdjecia"
        src="../../img/spotkanie7.jpg"
        alt="spotkanie autorskie z dziećmi"
      />
      <img
        class="zdjecia"
        src="../../img/spotkanie8.jpg"
        alt="spotkanie autorskie z dziećmi"
      />
      <img
        class="zdjecia"
        src="../../img/spotkanie9.jpg"
        alt="podpisywanie autografów"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'SpotkanieZdjecia',
}
</script>

<style>
.row {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.zdjecia {
  margin: 5px 0;
  width: 290px;
  height: 160px;
}

@media (min-width: 768px) {
  .row {
    flex-direction: row;
    align-items: center;
    flex-wrap: wrap;
    justify-content: center;
  }

  .zdjecia {
    margin: 10px;
    width: 500px;
    height: 260px;
  }
}
</style>