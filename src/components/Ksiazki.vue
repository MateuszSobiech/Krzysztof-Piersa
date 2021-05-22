<template>
  <div class="ksiazkiWrapper">
    <div class="tytul">Ksiązki</div>
    <div class="podtytul">
      <i>
        "O czym jest moja fantastyka? O bobrowatych stworkach, które ocaliły
        cesarstwo ludzi przed inwazją robali z księżyca za pomocą wielkiego
        robota. Wszystko jasne, nie?"
      </i>
    </div>
    <div class="ksiazki">
      <div class="kOpis">
        <img class="img" src="../../img/k1.jpg" alt="" />
        <p>
          Choć gry komputerowe są w naszych domach od niemal trzydziestu lat,
          wiedza w ich temacie wydaje się być znikoma. Cienka granica pomiędzy
          pasją, a uzależnieniem zaciera się coraz bardziej. Jak rozpoznać
          uzależnienie od gier? Jak z nim walczyć?
        </p>
        <p>
          Krzysztof Piersa sam był uzależniony od gier komputerowych. Pokonał je
          jednak własnymi siłami, a swoją historię spisał ku przestodze innych
          graczy. Pokazuje zarówno dobre jak i złe strony grania, a także
          konsekwencje wielogdzinnego przesiadywania przed komputerem.
        </p>
        <p>
          "Komputerowy ćpun" jest uznawany za pierwszy rzetelny poradnik
          dotyczący uzależnienia od gier komputerowych wydany w Polsce.
        </p>
      </div>

      <div class="kOpis">
        <img class="img" src="../../img/k2.png" alt="" />
        <p>
          Żyjemy w świecie nieograniczonych możliwośći. Osiągnięcia człowieka
          zapierają dech w piersiach, a niemożliwe stoi pod znakiem zapytania.
          Mimo to wielu ludzi nadal zadaje sobie pytania: Jak nazwać?, Jak
          zaplanować?, Jak zrealizować swoje marzenia? Wystawieni na krytykę i
          wszechogarniającą opinię publiczną boimy się realizować planów
          zagnieżdżonych na dnie serca. Do szkoły przychodzi marzyciel, opuszcza
          ją operator wózka widłowego.
        </p>
        <p>
          Nie są nam jednak potrzebne specjalne kursy i złote rady. Potrzebujemy
          jedynie odrobiny treningu w realizacji swoich marzeń. Krzysztof Piersa
          zrealizował już 98% własnych, życiowych planów. Co chcesz osiągnąć i
          jak chcesz to zrobić? Ten poradnik pozwoli CI znaleźć odpowiedź na
          pytanie.
        </p>
      </div>

      <div class="kOpis">
        <img class="img" src="../../img/k3.jpg" alt="" />
        <p>
          Yonzi Chamarovitch jest bohaterem Sory. Konstruktorem i pilotem
          "Kolosa", najpotężniejszego robota bojowego, który ocalił Cesarstwo
          przed inwazją Księżycowej Szarańczy - kosmicznego szkodnika siejącego
          w galaktyce zagładę.
        </p>
        <p>
          Na swoje nieszczęście Yonzi jest Mik-Makiem, małym bobrowatym
          futrzakiem, którego nikt prócz pobratymców nie traktuje poważnie.
          Cesarz nie ma jednak wyboru i właśnie Chamarovitch staje na czele
          międzyplanetarnej misji mającej zdobyć surowce na budowę całej armii
          "Kolosów". Drużyna, a raczej załoga złożona z ludzi i Mik-Maków to
          prawdziwa beczka prochu, która czeka tylko na to, aby eksplodować... i
          eksploduje.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.ksiazkiWrapper {
  padding: 15px;
  background-color: white;
  text-align: center;
}
.tytul {
  font-size: 2.5rem;
  text-align: center;
  font-weight: 700;
}
.podtytul {
  padding: 5px 15px 15px 15px;
}
.ksiazki {
  display: flex;
  flex-direction: column-reverse;
}
.img {
  padding-top: 15px;
  width: 50%;
  height: auto;
}
.kOpis {
  flex: 1 1 0px;
  border: 3px rgb(77, 159, 236) ridge;
  border-radius: 15px;
  padding: 0 15px;
  margin: 10px 15px;
}

@media (min-width: 768px) {
  .podtytul {
    max-width: 600px;
    margin: auto;
  }
  .ksiazki {
    display: flex;
    flex-direction: row;
    flex-grow: 1;
  }
}
</style>