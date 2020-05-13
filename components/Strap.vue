<template>
  <section class="banner">
    <h2 class="banner__text">
      и в отличие от рака, <span class="banner__text_bold">#этонелечится</span>
    </h2>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.banner {
  max-width: 1320px;
  min-height: 86px;
  margin: auto;
  background-color: #613a93;
  display: flex;
}

.banner__text {
  max-width: 750px;
  margin: 20px auto;
  font-family: Inter;
  font-weight: normal;
  font-size: 30px;
  line-height: 46px;
  color: #fff;
  text-align: center;
  text-transform: uppercase;
}

.banner__text_bold {
  font-weight: 800;
  font-size: 40px;
}
</style>
