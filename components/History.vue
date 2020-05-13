<template>
  <section class="tell-story">
    <div class="tell-story__inner">
      <h2 class="title">Расскажите свою историю</h2>
      <div class="tell-story__container">
        <div class="section-about section-about__tell-story">
          <p class="description">
            Мы публикуем новые истории на сайте раз в неделю. Есть 2 варианта
            поделиться своей историей неизлечимых привычек, навязчивых идей и
            болезненных привязанностей.
          </p>
        </div>
        <div class="tell-story__options">
          <h3 class="description_bold">1-й вариант</h3>
          <h3 class="description_bold description_dim">2-й вариант</h3>
        </div>
        <div class="tell-story__info">
          <p class="description description__tell-story">
            Заполнить подробную форму прямо на сайте и мы опубликуем вашу
            историю после проверки. Пожалуйста, заполняйте все пункты корректно,
            если вы испытаете какие-то сложности, воспользуйтесь 2-м вариантом.
          </p>
          <p class="description description__tell-story description_invisible">
            Оставить контакт (почту или номер телефона) и мы свяжемся с вами,
            зададим вопросы, уточним детали вашей истории.
          </p>
          <button class="button button__tell-story">Заполнить форму</button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.title {
  font-family: Inter;
  font-weight: 600;
  font-size: 32px;
  line-height: 36px;
  margin: 0 0 32px 0;
  color: #000;
  max-width: 413px;
}

.tell-story {
  max-width: 1440px;
  max-height: 552px;
  background-color: #f7f7f7;
  margin: auto;
}

.tell-story__inner {
  max-width: 1320px;
  margin: auto;
  padding: 100px 0;
  background-color: #f7f7f7;
}

.tell-story__container {
  display: flex;
}

.section-about {
  max-width: 413px;
  width: 413px;
  margin: 0;
}

.section-about.section-about__tell-story {
  margin: 0 120px 0 0;
}

.section-about.section-about__insta {
  margin: 0 37px 0 0;
}

.tell-story__info {
  max-width: 640px;
  height: 110px;
}

.tell-story__options {
  margin: 0 40px 0 0;
}

.description {
  max-width: 340px;
  margin: 0;
  font-family: Inter;
  font-size: 18px;
  line-height: 22px;
  color: #666;
}

.description__tell-story {
  max-width: 640px;
}

.description_bold {
  font-family: Inter;
  font-weight: 500;
  margin: 0 0 10px 0;
}

.description_bold:last-child {
  margin: 0;
}

.description_dim {
  color: #a2a2a2;
}

.description_invisible {
  display: none;
}

.button {
  background-color: #613a93;
  color: #fff;
  font-weight: 500;
  font-size: 16px;
  line-height: 19px;
  text-align: center;
}

.button__tell-story {
  width: 280px;
  height: 52px;
  margin: 76px 0;
}
</style>
