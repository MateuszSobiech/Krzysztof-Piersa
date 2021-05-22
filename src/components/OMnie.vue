<template>
  <div class="wrapperOMnie">
    <div class="openOMnie" @click="openOMnie">
      <div>O Mnie</div>
      <div id="arrow" class="arrow-margin"><span>&#10095;</span></div>
    </div>
    <Opis id="opis" class="czyOMnie" />
  </div>
</template>

<script>
import Opis from './Opis.vue'

export default {
  name: 'OMnie',
  components: {
    Opis
  },
  methods: {
    openOMnie: function () {
      const opis = document.getElementById('opis')
      const arrow = document.getElementById('arrow')
      opis.classList.toggle('czyOMnie')
      arrow.classList.toggle('arrow')
    }
  },
};
</script>

<style >
.wrapperOMnie {
  text-align: center;
  padding: 10px 15px;
  font-weight: 700;
  font-size: 40px;
  color: white;
  background-color: rgb(77, 159, 236);
}

.wrapperOMnie p {
  font-weight: 300;
  text-align: left;
  font-size: 16px;
  color: white;
  margin-top: 20px;
}

.wrapperOMnie p:first-child {
  font-weight: 300;
  text-align: left;
  font-size: 16px;
  color: white;
  margin-top: 10px;
}

.openOMnie {
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
}

.czyOMnie {
  display: none;
}

.arrow-margin {
  margin-left: 20px;
  transition: all 0.3s ease-in-out;
}

.arrow {
  transform: rotate(90deg);
}

@media (min-width: 768px) {
  .wrapperOMnie p {
    font-weight: 300;
    text-align: center;
    font-size: 20px;
    color: white;
    margin-top: 20px;
  }

  .arrow-margin {
    display: none;
  }

  .openOMnie {
    cursor: text;
  }

  .czyOMnie {
    display: block;
  }
}
</style>