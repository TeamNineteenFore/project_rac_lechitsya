<template>
  <section class="insta">
    <div class="section-about section-about__insta">
      <a
        href="https://www.instagram.com/raklechitsa/"
        target="_blank"
        class="link"
        ><h2 class="title">Инстаграм</h2></a
      >
      <p class="description">
        Два раза в неделю мы просматриваем все посты по хештегу #этонелечится.
        Все истории, где нет нецензурных выражений и запрещенного контента
        попадают сюда. Следите за правильным написанием хештега, чтобы мы не
        пропустили вашу историю.
      </p>
    </div>
    <div class="insta-grid">
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
      <div class="insta-grid__item"></div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.insta {
  max-width: 1320px;
  margin: auto;
  display: flex;
  padding: 100px 0;
}

.section-about {
  max-width: 413px;
  width: 413px;
  margin: 0;
}

.section-about.section-about__insta {
  margin: 0 37px 0 0;
}

.insta-grid {
  margin: 0;
  display: grid;
  grid-gap: 30px;
  grid-template: repeat(2, 1fr) / repeat(4, 1fr);
  justify-content: center;
}

.insta-grid__item {
  width: 195px;
  height: 195px;
  object-fit: cover;
  background-color: #ededed;
}

.link {
  color: #000;
}

.title {
  font-family: Inter;
  font-weight: 600;
  font-size: 32px;
  line-height: 36px;
  margin: 0 0 32px 0;
  color: #000;
  max-width: 413px;
}
</style>
