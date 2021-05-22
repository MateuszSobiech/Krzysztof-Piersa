<template>
  <div class="ofertaWrapper">
    <div class="lewaGrupa">
      <div class="ofertaDiv">
        <h2>
          Przeciwdziałania uzależnienia od gier komputerowych telefonów
          komórkowych i internetu
        </h2>
        <p>
          W jaki sposób rozpoznawać uzależnienie i z nim walczyć? Konsekwencje
          wielogodzinnego przesiadywania przed monitorem. Plusy i minusy
          korzystania z gier komputerowych. Największe zagrożenia w internecie.
          Wykład kierowany zarówno do nauczycieli i rodziców jak i młodzieży.
        </p>
      </div>
      <div class="ofertaDiv">
        <h2>Warsztaty realizacji marzeń i radzenia sobie z krytyką</h2>
        <p>
          W jaki sposób zaplanować realizację swojego marzenia? Wytyczenie
          ścieżki zawodowej. Określenie przeciwwskazań wewnętrznych i
          zewnętrznych. Odróżnienie krytyki od hejtu i reagowanie na nie.
        </p>
      </div>
    </div>
    <div class="ofertaDiv">
      <h2>Warsztaty literackie</h2>
      <p>
        Od pomysłu do publikacji. Jako doświadczony dziennikarz, autor dwóch
        poradników i książek fantastycznych Krzysztof radzi początkującym
        wojownikom pióra i aspirującym pisarzom jak okiełznać swoją twórczość. W
        skład zagadnień wchodzą:
      </p>
      <ol>
        <li>Określenie tematu i grupy odbiorcznej książki</li>
        <li>
          Określenie profilu wydawniczego (Wydawnictwo tradycyjne,
          self-publishing, vanity press)
        </li>
        <li>
          Budowanie fabuły, czasu, miejsca akcji, bohaterów i świata
          przedstawionego
        </li>
        <li>
          Szkielet powieści (wstęp, rozwinięcie, zwrot akcji, zakończenie)
        </li>
        <li>Części składowe powieści (dialogi i opisy)</li>
        <li>
          Narzędzia literackie (budowanie słownictwa, zabiegi literackie,
          sztuczki pisarzy, tempo akcji)
        </li>
        <li>Walka z weną, prokrastynacją i krytką</li>
        <li>Sylwetka pisarza</li>
        <li>Organizacja spotkań autorskich</li>
        <li>Rozmawianie z wydawnictwem</li>
        <li>Wydawanie książki samodzielnie</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Oferta'
}
</script>

<style>
.ofertaWrapper {
  margin-top: 15px;
  color: white;
}

.ofertaDiv {
  margin-top: 15px;
  border: 1px solid white;
  padding: 0 15px;
  border-radius: 15px;
}

.ofertaDiv ol {
  text-align: left;
}

@media (min-width: 768px) {
  .ofertaWrapper {
    display: flex;
  }
  .ofertaDiv {
    margin: 20px;
    padding: 20px 50px;
  }
  .lewaGrupa {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
}
</style>