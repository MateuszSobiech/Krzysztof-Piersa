<template>
  <div class="terapiaWrapper">
    <div class="spotkaniaTytul">Terapia uzależnień</div>
    <div class="spotkaniaOpis">
      Jako licencjonowany terapeuta ds. uzależnień, Krzysztof Piersa prowadzi
      również indywidualne konsultacje terapeutyczne. Zajmując się głównie
      uzależnieniem od gier komputerowych, telefonów komórkowych oraz Internetu,
      udziela specjalistycznych porad i prowadzi pełną terapię zarówno wśród
      nieletnich jak i dorosłych. Pomaga zrozumieć złożoność uzależnienia, jego
      genezę a także wskazać najlepszą drogę opanowania problemu.
    </div>
    <div class="cenaDiv">
      <p><b>Konsultacje terapeutyczne objęte są pełną animowością.</b></p>
      <p class="cena">
        Z uwagi na częste warsztaty w terenie proszę o wcześniejszy kontakt
        mailowy lub telefoniczny. Koszt doradztwa terapeutycznego to 120zł.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Terapia'
}
</script>

<style>
.terapiaWrapper {
  text-align: center;
  padding: 10px 15px;
  color: white;
  background-color: rgb(77, 159, 236);
}
.cenaDiv {
  margin-top: 35px;
}
.cenaDiv p {
  margin-bottom: 5px;
}

.cena {
  margin: 0;
  font-size: 20px;
}

@media (min-width: 768px) {
}
</style>