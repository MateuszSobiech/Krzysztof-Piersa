<template>
  <div class="mediaWrapper">
    <div class="tytul">W mediach i internecie</div>
    <div class="podtytul">
      Krzysztof Piersa wielokrotnie pojawiał się w mediach jako
      <b>specjalista do spraw uzależnień od gier komputerowych i internetu.</b>
      Prowadzi on również swój własny kanał na YouTube, gdzie umieszca vlogi.
    </div>
    <Video />
    <div class="socialMedia">
      <img class="socialImg" src="../../img/media1.jpg" alt="media1" />
      <img class="socialImg" src="../../img/media2.jpg" alt="media2" />
      <img class="socialImg2" src="../../img/media3.jpg" alt="media3" />
    </div>
  </div>
</template>

<script>
import Video from './Video.vue'
export default {
  name: 'Media',
  components: { Video }
}
</script>

<style>
.mediaWrapper {
  padding: 15px;
  background-color: white;
  text-align: center;
}
.socialImg {
  margin-top: 15px;
  width: 100%;
}

@media (min-width: 768px) {
  .socialMedia {
    margin-top: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .socialMedia img {
    width: 20%;
  }

  .socialImg2 {
    margin-top: 10px;
    width: 8% !important;
  }
}
</style>