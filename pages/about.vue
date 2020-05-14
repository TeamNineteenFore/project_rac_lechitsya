<template>
  <div class="about">
    <h2 class="title">Истории</h2>
    <Footer />
  </div>
</template>

<script>
import Footer from '@/components/Footer';
export default {
  components: {
    Footer: Footer,
  },
};
</script>

<style scoped>
.about {
  max-width: 1440px;
  margin: 0 auto;
}
.title {
  margin-top: 20vh;
  text-align: center;
  height: 35vh;
}
</style>
