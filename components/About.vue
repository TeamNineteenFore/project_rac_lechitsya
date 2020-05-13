<template>
  <section class="about about_indent">
    <div class="about__edges">
      <h2 class="title title_about">#РАКЛЕЧИТСЯ</h2>
      <h3 class="title title_small">О проекте</h3>
      <div class="about__items">
        <p class="about__text-create">
          Этот проект был создан благотворительным фондом Константина
          Хабенского.
        </p>
        <div class="about__main">
          <blockquote class="about__quote">
            <p class="about__bq">Рак Лечится</p>
            <cite class="about__cite">Фонд Хабенского</cite>
          </blockquote>
          <ul class="about__text-items">
            <li class="about__text">
              Есть вещи, которые не лечатся. Особенности характера, страстные
              увлечения, привычки, ставшие частью нашего «я», фобии, которые мы
              приобрели в детстве. Список можно продолжать до бесконечности, но
              одна болезнь в него точно не войдет. Эта болезнь — рак. Рак
              лечится, и лучшее доказательство — люди с их неизлечимыми
              особенностями, которые сумели победить рак.
            </li>
            <li class="about__text">
              Рак лечится — проект Благотворительного Фонда Константина
              Хабенского и Leo Burnett Moscow. С его помощью мы надеемся
              изменить отношение людей к раку и заставить каждого поверить:
              онкологическое заболевание — это не приговор.
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.about {
  background-color: #613a93;
  width: 100%;
  margin: 0;
}

.about__bq {
  padding: 0;
  margin: 0 0 10px auto;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 1.22;
  max-width: 111px;
  /* identical to box height, or 122% */
  text-align: right;
  color: #ffffff;
}

.about__cite {
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 1.22;
  /* identical to box height, or 122% */
  text-align: right;
  color: #c9c9c9;
}

.about__edges {
  margin: 0 auto;
  max-width: 1440px;
  padding-bottom: 100px;
}

.about__items {
  margin-top: 32px;
  display: flex;
  position: relative;
  justify-content: space-between;
  padding: 0 60px 0 60px;
}

.about__main {
  padding: 0;
  display: grid;
  grid-template-columns: 250px 640px;
  grid-column-gap: 40px;
  grid-template-rows: min-content;
}

.about__quote {
  grid-column: 1 / 2;
  grid-row: 1 / 2;
  margin: 0;
  padding: 0;
  text-align: right;
  align-items: start;
}

.about__text-create {
  margin: 0 auto auto 0;
  padding: 0;
  max-width: 305px;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 1.22;
  /* or 125% */
  color: #dedede;
}

.about__text-items {
  margin: 0;
  padding: 0;
  grid-column: 2 / 3;
  grid-row: 1 / 2;
}

.about__text {
  list-style: none;
  margin: 0 0 22px 0;
  padding: 0;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 1.22;
  /* or 122% */
  color: #dedede;
}
.about__text:last-of-type {
  margin: 0;
}

.about_indent {
  padding: 0;
  margin: 0 auto;
}

.title_about {
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 77px;
  text-align: center;
  color: #ffffff;
  margin: 0 auto 75px auto;
  padding-top: 90px;
  padding-left: 0;
}

.title_small {
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 1.12;
  /* identical to box height, or 112% */
  color: #ffffff;
  padding-top: 0;
  padding-left: 0;
  margin-left: 60px;
}
</style>
