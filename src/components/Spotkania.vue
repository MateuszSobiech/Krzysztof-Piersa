<template>
  <div class="spotkaniaWrapper">
    <div class="spotkaniaTytul">Spotkania autorskie i wykłady</div>
    <div class="spotkaniaOpis">
      Krzysztof Piersa prowadzi <b>spotkania autorskie</b> zarówno w szkołach,
      bibliotekach i w domach kultury. Spotkania mogą być prowadzone w sposób
      ogólny lub skupić się na konkretnej publikacji. Prowadzi również wykłady i
      szkolenia.
    </div>
    <SpotkanieZdjecia />
    <Oferta />
  </div>
</template>

<script>
import SpotkanieZdjecia from './SpotkanieZdjecia.vue'
import Oferta from './Oferta.vue'
export default {
  name: 'Spotkania',
  components: {
    SpotkanieZdjecia, Oferta
  }
}
</script>

<style>
.spotkaniaWrapper {
  text-align: center;
  padding: 10px 15px 25px 15px;
  color: white;
  background-color: rgb(77, 159, 236);
}
.spotkaniaTytul {
  font-weight: 700;
  font-size: 40px;
  margin-bottom: 15px;
}
.spotkaniaOpis {
  font-size: 20px;
  padding: 10px 0px;
}

@media (min-width: 768px) {
  .spotkaniaTytul {
    margin: auto;
    width: 40%;
  }
  .spotkaniaOpis {
    margin: auto;
    width: 60%;
  }
}
</style>