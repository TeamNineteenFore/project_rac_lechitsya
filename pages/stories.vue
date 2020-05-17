<template>
  <Container>
    <h2 class="title">Истории</h2>
  </Container>
</template>

<script>
import Container from '@/components/Container';
export default {
  components: {
    Container,
  },
};
</script>

<style scoped>
.stories {
  max-width: 1440px;
  margin: 0 auto;
}
.title {
  margin-top: 20vh;
  text-align: center;
  height: 35vh;
}
</style>
