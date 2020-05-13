<template>
  <div class="stories__section">
    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Владимир Тен</h3>
      <p class="card__description">
        Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Владимир Познер</h3>
      <p class="card__description">
        Я боюсь акул — и, в отличии от рака, это не лечится.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Александр Тарханов</h3>
      <p class="card__description">
        Я не могу победить свою пунктуальность в отличии от рака.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Владимир Тен</h3>
      <p class="card__description">
        Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Владимир Тен</h3>
      <p class="card__description">
        Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Владимир Познер</h3>
      <p class="card__description">
        Я боюсь акул — и, в отличии от рака, это не лечится.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Александр Тарханов</h3>
      <p class="card__description">
        Я не могу победить свою пунктуальность в отличии от рака.
      </p>
    </div>

    <div class="card">
      <img src="../src/image/photo.jpg" alt="Photo" class="card__image" />
      <h3 class="card__title">Владимир Тен</h3>
      <p class="card__description">
        Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.
      </p>
    </div>

    <button class="stories__button">Больше статей</button>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.stories {
  padding: 0 60px;
}

.stories__title {
  font-family: Inter;
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 112%;
  color: #000000;
  max-width: 413px;
  padding: 100px 0 70px;
}

.stories__section {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 300px));
  grid-template-rows: minmax(0, auto);
  column-gap: 40px;
  row-gap: 70px;
  margin-bottom: 70px;
}

.stories__button {
  background-color: #fbfbfb;
  border: none;
  width: 100%;
  height: 82px;
  margin-bottom: 100px;
}

.card {
  display: flex;
  flex-direction: column;
}

.card__image {
  width: 100%;
}

.card__title {
  font-family: Inter;
  font-style: normal;
  font-weight: 600;
  font-size: 22px;
  line-height: 100%;
  color: #000000;
  padding: 20px 0 14px;
}

.card__description {
  font-family: Inter;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 129%;
  color: #666666;
  max-width: 250px;
}
</style>
