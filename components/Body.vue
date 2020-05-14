<template>
  <div>
    <cover />
    <video-stories />
    <strap>и в отличие от рака,</strap>
    <stories />
    <strap />
    <insta />
    <history />
    <statistics />
    <about />
  </div>
</template>

<script>
import Cover from '@/components/Cover';
import Video from '@/components/Video';
import Strap from '@/components/Strap';
import Stories from '@/components/Stories';
import Insta from '@/components/Insta';
import History from '@/components/History';
import Statistics from '@/components/Statistics';
import About from '@/components/About';

export default {
  components: {
    cover: Cover,
    'video-stories': Video,
    strap: Strap,
    stories: Stories,
    insta: Insta,
    history: History,
    statistics: Statistics,
    about: About,
  },
};
</script>

<style scoped>
/* .video-stories {
  margin: 100px auto;
} */
</style>
