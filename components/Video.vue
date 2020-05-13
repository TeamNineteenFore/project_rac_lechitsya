<template>
  <div class="video-stories main__video-stories">
    <h2 class="video-stories__title">
      Истории людей, победивших рак, но не свои привычки
    </h2>
    <p class="video-stories__desription">
      Есть вещи, которые не лечатся. Вещи ставшие частью нашего «я», фобии,
      страхи. Но это точно не рак. Рак лечится. Лучшее доказательство — люди с
      их историями.
    </p>
    <div class="arrow-btns">
      <button
        class="arrows-btns__btn arrows-btns__btn-left"
        type="button"
        disabled
      ></button>
      <button
        class="arrows-btns__btn arrows-btns__btn-right arrows-btns__btn-right_active"
        type="button"
      ></button>
    </div>
    <div class="video-stories__video">
      <iframe class="video-stories__iframe" src="#" frameborder="0"></iframe>
      <button class="video-stories__play-button" type="button"></button>
    </div>
    <p class="video-stories__caption">
      Все видео вы можете найте на нашем
      <a href="#" target="_blank" class="video-stories__caption"
        >YouTube канале.</a
      >
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.video-stories {
  max-width: 1340px;
  display: grid;
  grid-template-columns: minmax(0, 413px) minmax(0, 867px);
  grid-template-rows: repeat(4, auto);
  grid-template-areas:
    'title video'
    'description video'
    'buttons video'
    '. caption';
  grid-column-gap: 40px;
}
.video-stories__title {
  width: 100%;
  font-size: 32px;
  line-height: 36px;
  grid-area: title;
  margin: 0 0;
  font-weight: 600;
  padding: 0 0;
}

.video-stories__desription {
  max-width: 340px;
  font-size: 18px;
  line-height: 22px;
  grid-area: description;
  margin: 0 0;
  padding: 0 0;
}

.video-stories__video {
  position: relative;
  grid-area: video;
}
.video-stories__iframe {
  background-color: #ededed;
  margin: 0 0 10px 0;
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 51.9%;
}

.video-stories__play-button {
  background-image: url('../src/image/video-button-play.png');
  position: absolute;
  width: 90px;
  height: 90px;
  top: calc(50% - 45px);
  left: calc(50% - 45px);
  border: none;
  background-color: transparent;
  cursor: pointer;
}

.video-stories__caption {
  font-size: 12px;
  line-height: 16px;
  grid-area: caption;
  color: black;
}

.arrow-btns {
  position: relative;
  display: flex;
  justify-content: space-between;
  max-width: 80px;
  grid-area: buttons;
  align-items: flex-end;
}

.arrows-btns__btn {
  width: 40px;
  height: 40px;
  border: none;
  background-color: #ededed;
  background-repeat: no-repeat;
  background-position: center;
  padding: 0;
  cursor: pointer;
}

.arrows-btns__btn-right {
  background-image: url('../src/image/arrow-right.svg');
  grid-area: button-right;
}

.arrows-btns__btn-left {
  background-image: url('../src/image/arrow-left.svg');
  grid-area: button-left;
}

.arrows-btns__btn-right_active {
  background-image: url('../src/image/arrow-right_active.svg');
}

.arrows-btns__btn-left_active {
  background-image: url('../src/image/arrow-left_active.svg');
}

@media screen and (max-width: 1280px) {
  .video-stories__title {
    font-size: 28px;
    line-height: 32px;
    max-width: 367px;
  }

  .video-stories__description {
    font-size: 16px;
    line-height: 20px;
  }
}

@media screen and (max-width: 1024px) {
  .video-stories__title {
    font-size: 24px;
    line-height: 28px;
    max-width: 288px;
  }

  .video-stories__description {
    font-size: 13px;
    line-height: 16px;
  }

  .video-stories__title {
    max-width: 380px;
  }
}
</style>
