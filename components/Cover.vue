<template>
  <div class="cover main__cover">
    <video class="cover__video">
      <source
        src="video.mp4"
        type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'
      />
      <source src="video.ogg" type='video/ogg; codecs="theora, vorbis"' />
      <source src="video.webm" type='video/webm; codecs="vp8, vorbis"' />
    </video>
    <h1 class="cover__title">#РАКЛЕЧИТСЯ</h1>
    <a href="#" class="cover__button"></a>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.cover {
  position: relative;
}

.cover__video {
  background-color: #613a93;
  position: relative;
  width: 100%;
  height: 100vh;
}

.cover__title {
  position: absolute;
  font-size: 92px;
  line-height: 111px;
  color: #ffffff;
  font-weight: 800;
  text-align: center;
  width: 718px;
  top: calc(50% - 55.5px);
  left: calc(50% - 359px);
  z-index: 1;
}

.cover__button {
  /* background-image: url("image/cover-button.svg"); */
  background-image: url('../src/image/cover-button.svg');
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  position: absolute;
  width: 36px;
  height: 12px;
  bottom: 40px;
  left: calc(50% - 18px);
  border: none;
  cursor: pointer;
  z-index: 1;
}

@media screen and (max-width: 1280px) {
  .cover__title {
    font-size: 78px;
    line-height: 94px;
  }
}

@media screen and (max-width: 768px) {
  .cover__title {
    font-size: 64px;
    line-height: 77px;
  }
}
</style>
