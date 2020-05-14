<template>
  <div class="stories">
    <Title class="stories__title">
      Истории неизлечимых привычек
    </Title>

    <div class="stories__section">
      <Card
        v-for="card in Cards"
        :key="card.id"
        :name="card.name"
        :quote="card.quote"
      />
    </div>

    <button class="stories__button">Больше статей</button>
  </div>
</template>

<script>
import Title from '@/components/ui/Title';
import Card from '@/components/ui/Card';
export default {
  components: {
    Card: Card,
    Title: Title,
  },
  data() {
    return {
      Cards: [
        {
          id: 1,
          name: 'Владимир Тен',
          quote:
            'Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.',
        },
        {
          id: 2,
          name: 'Владимир Познер',
          quote: 'Я боюсь акул — и, в отличии от рака, это не лечится.',
        },
        {
          id: 3,
          name: 'Александр Тарханов',
          quote: 'Я не могу победить свою пунктуальность в отличии от рака.',
        },
        {
          id: 1,
          name: 'Владимир Тен',
          quote:
            'Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.',
        },
        {
          id: 2,
          name: 'Владимир Познер',
          quote: 'Я боюсь акул — и, в отличии от рака, это не лечится.',
        },
        {
          id: 3,
          name: 'Александр Тарханов',
          quote: 'Я не могу победить свою пунктуальность в отличии от рака.',
        },
        {
          id: 1,
          name: 'Владимир Тен',
          quote:
            'Я всегда читаю книги с конца, - и это не лечится, в отличие от рака.',
        },
        {
          id: 2,
          name: 'Владимир Познер',
          quote: 'Я боюсь акул — и, в отличии от рака, это не лечится.',
        },
      ],
    };
  },
};
</script>

<style scoped>
.stories {
  padding: 0 60px;
}

.stories__title {
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
  padding: 31px 0;
  margin-bottom: 100px;
  font-family: Inter;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 20px;
  display: flex;
  justify-content: center;
}
</style>
