<template>
  <section class="statistics statistics_indent">
    <h3 class="title">Статистика по онкозаболеваниям</h3>
    <div class="statistics__items">
      <div class="statistics__item">
        <p class="statistics__text">
          Каждый 3-й в стране уверен, что рак неизлечим. А это примерно 48 918
          000 человек.
        </p>
        <div class="progress-bar">
          <div class="progress-bar__fill"></div>
        </div>
        <p class="statistics__numbers">1 из 3</p>
        <p class="statistics__source">Левада-Центр 2018</p>
      </div>
      <div class="statistics__item">
        <p class="statistics__text">2,6% Россиян имеют онкозаболевания.</p>
        <div class="progress-bar">
          <div class="progress-bar__fill"></div>
        </div>
        <p class="statistics__numbers">3 700 000</p>
        <p class="statistics__source">Росстат 2018</p>
      </div>
      <div class="statistics__item">
        <p class="statistics__text">
          На 28% выросла доля выявления заболеваний на ранней стадии за 10 лет.
        </p>
        <div class="progress-bar">
          <div class="progress-bar__fill"></div>
        </div>
        <p class="statistics__numbers">↑28%</p>
        <p class="statistics__source">МНИОИ Герцена 2018</p>
      </div>
      <div class="statistics__item">
        <p class="statistics__text">
          На 25% снизилась смертность в течение первого года после постановки
          диагноза.
        </p>
        <div class="progress-bar">
          <div class="progress-bar__fill"></div>
        </div>
        <p class="statistics__numbers">↓25%</p>
        <p class="statistics__source">МНИОИ Герцена 2018</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.statistics {
  max-width: 1440px;
  /* выше установили ограничение по максимальной ширине */
  width: 100%;
  background-color: #ffffff;
}
.statistics__item {
  width: 300px;
  height: 300px;
  display: flex;
  position: relative;
  flex-direction: column;
}

.statistics__items {
  display: grid;
  position: relative;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  padding: 70px 60px 100px 60px;
  margin: 0;
}

.statistics__numbers {
  max-width: 260px;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 38px;
  line-height: 1.05;
  /* identical to box height, or 105% */
  text-align: right;
  color: #000000;
  margin-bottom: 20px;
}

.statistics__source {
  max-width: 260px;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 1.33;
  /* identical to box height, or 133% */
  text-align: right;
  color: #666666;
  /*margin-bottom: 20px;*/
}

.statistics__text {
  max-width: 260px;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  height: 48px;
  line-height: 1.33;
  /* or 133% */
  color: #000000;
  margin: 20px 20px 76px 20px;
}

.progress-bar {
  max-width: 260px;
  height: 40px;
  background: #f4f4f4;
  position: relative;
  margin: 0 20px 20px 20px;
}

.progress-bar__fill {
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  background: #613a93;
  width: 30%;
}

.statistics_indent {
  padding: 0;
  margin: 0 auto;
}

.statistics {
  max-width: 1440px;
  /* выше установили ограничение по максимальной ширине */
  width: 100%;
  background-color: #ffffff;
}

.title {
  padding-left: 60px;
  padding-top: 100px;
  margin: 0;
  text-align: left;
  max-width: 413px;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 2rem;
  line-height: 1.12;
  /* or 112% */
  color: #000000;
}
</style>
