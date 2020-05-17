<template>
  <Container>
    <div class="insta__inner">
      <div class="section-about section-about__insta">
        <a
          href="https://www.instagram.com/raklechitsa/"
          target="_blank"
          class="link"
          ><Title class="title">Инстаграм</Title></a
        >
        <Description>
          Два раза в неделю мы просматриваем все посты по хештегу #этонелечится.
          Все истории, где нет нецензурных выражений и запрещенного контента
          попадают сюда. Следите за правильным написанием хештега, чтобы мы не
          пропустили вашу историю.
        </Description>
      </div>
      <insta-grid />
    </div>
  </Container>
</template>

<script>
import Title from '@/components/ui/Title';
import Description from '@/components/ui/Description';
import InstaGrid from '@/components/ui/InstaGrid';
import Container from '@/components/Container';
export default {
  components: {
    Title,
    Description,
    'insta-grid': InstaGrid,
    Container,
  },
};
</script>

<style scoped>
.insta__inner {
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

.link {
  color: #000;
}

.title {
  margin: 0 0 32px 0;
  max-width: 413px;
}
</style>
