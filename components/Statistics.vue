<template>
  <section class="statistics statistics_indent">
    <Title>Статистика по онкозаболеваниям</Title>
    <StaticsItem class="statistics__item" />
  </section>
</template>

<script>
import Title from '@/components/ui/Title';
import StaticsItem from '@/components/ui/StaticsItems';

export default {
  components: {
    Title,
    StaticsItem,
  },
};
</script>

<style scoped>
.statistics {
  max-width: 1440px;
  width: 100%;
  background-color: #ffffff;
}

.statistics__item {
  margin-top: 70px;
}

.statistics_indent {
  margin: 100px auto;
}
</style>
