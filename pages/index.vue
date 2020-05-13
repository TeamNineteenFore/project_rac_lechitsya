<template>
  <div class="page">
    <main-body />
    <!-- <Footer/> -->
  </div>
</template>

<script>
import Body from '@/components/Body';
// import Footer from '@/components';

export default {
  components: {
    'main-body': Body,
  },
  data() {
    return {
      text: '',
    };
  },
};
</script>

<style>
.page {
  max-width: 1440px;
  margin: 0 auto;
}
</style>
