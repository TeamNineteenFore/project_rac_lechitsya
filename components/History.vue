<template>
  <section class="history">
    <div class="history__inner">
      <Title>
        Расскажите свою историю
      </Title>

      <div class="history__container">
        <Description class="history__description_left">
          Мы публикуем новые истории на сайте раз в неделю. Есть 2 варианта
          поделиться своей историей неизлечимых привычек, навязчивых идей и
          болезненных привязанностей.
        </Description>
        <div class="history__switch">
          <span class="history__click history__click_active">1-й вариант</span>
          <span class="history__click">2-й вариант</span>
        </div>
        <Description class="history__description_right">
          Заполнить подробную форму прямо на сайте и мы опубликуем вашу историю
          после проверки. Пожалуйста, заполняйте все пункты корректно, если вы
          испытаете какие-то сложности, воспользуйтесь 2-м вариантом.
          <VioletButton class="history__button">Заполнить форму</VioletButton>
        </Description>
      </div>
    </div>
  </section>
</template>

<script>
import Title from '@/components/ui/Title';
import Description from '@/components/ui/Description';
import VioletButton from '@/components/ui/VioletButton';
export default {
  components: {
    Title: Title,
    Description: Description,
    VioletButton: VioletButton,
  },
};
</script>

<style scoped>
.history {
  max-width: 1440px;
  background-color: #f7f7f7;
  margin: 0 auto;
}

.history__inner {
  max-width: 1320px;
  margin: 0 auto;
  padding: 100px 0;
}

.history__container {
  display: flex;
  padding-top: 32px;
}

.history__description_left {
  max-width: 340px;
}

.history__description_right {
  max-width: 640px;
  margin-left: 40px;
  display: flex;
  flex-direction: column;
}

.history__switch {
  display: flex;
  flex-direction: column;
  margin-left: 192px;
}

.history__click {
  font-family: Inter;
  font-style: normal;
  font-size: 18px;
  line-height: 122%;
  padding-bottom: 10px;
  color: #a2a2a2;
}

.history__click_active {
  color: #000000;
  font-weight: 500;
}

.history__button {
  margin-top: 95px;
}
</style>
