<template>
  <div>
    <cover />
    <video-stories class="video-stories" />
    <strap />
    <stories />
  </div>
</template>

<script>
import Cover from '@/components/Cover';
import Video from '@/components/Video';
import Strap from '@/components/Strap';
import Stories from '@/components/Stories';
export default {
  components: {
    cover: Cover,
    'video-stories': Video,
    strap: Strap,
    stories: Stories,
  },
};
</script>

<style scoped>
.video-stories {
  margin: 100px auto;
}
</style>
