<template>
  <div class="cover main__cover">
    <cover-video />
    <hashtag class="cover__title">#РАКЛЕЧИТСЯ</hashtag>
    <a href="#" class="cover__button"></a>
  </div>
</template>

<script>
import Hashtag from '@/components/ui/Hashtag';
import CoverVideo from '@/components/ui/CoverVideo';

export default {
  components: {
    hashtag: Hashtag,
    'cover-video': CoverVideo,
  },
};
</script>

<style scoped>
.cover {
  position: relative;
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
