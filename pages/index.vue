<template>
  <div class="page">
    <main-body />
    <main-footer />
  </div>
</template>

<script>
import Body from '@/components/Body';
import Footer from '@/components/Footer';

export default {
  components: {
    'main-body': Body,
    'main-footer': Footer,
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
