<template>
  <div class="page">
    <Body />
    <Footer />
  </div>
</template>

<script>
import Body from '@/components/Body';
import Footer from '@/components/Footer';
import Header from '@/components/Header';

export default {
  components: {
    Header,
    Body,
    Footer,
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
  margin: 0 auto;
}
</style>
