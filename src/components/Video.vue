<template>
  <div class="videoWrapper">
    <div class="videoBox">
      <p><b>Spotkanie z Krzysztofem Piersą w Choszczno</b></p>
      <div class="video">
        <iframe
          width="100%"
          height="100%"
          src="https://www.youtube.com/embed/NtCFm6Dfd4s"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
    <div class="videoBox">
      <p><b>Wywiad na kanale "7 metrów pod ziemią"</b></p>
      <div class="video">
        <iframe
          width="100%"
          height="100%"
          src="https://www.youtube.com/embed/7p51SucQ91Y"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
    <div class="videoBox">
      <p><b>Kosmiczne Bobry na WTK</b></p>
      <div class="video">
        <iframe
          width="100%"
          height="100%"
          src="https://www.youtube.com/embed/lvmxzHcfC7E"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Video'
}
</script>

<style>
.videoBox p {
  margin-bottom: 5px;
}

.video {
  width: 100%;
}

@media (min-width: 768px) {
  .video {
    width: 100%;
    height: 350px;
  }
}

@media (min-width: 1100px) {
  .videoWrapper {
    display: flex;
  }

  .videoBox {
    width: 33.33%;
    margin-top: auto;
    margin-left: 20px;
    margin-right: 15px;
  }
  .video {
    width: 100%;
    height: 300px;
  }
}
</style>