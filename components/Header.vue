<template>
  <header class="header">
    <h1 class="header__logo">
      Проект Благотворительного Фонда Константина Хабенского
    </h1>
    <div class="header__navigation">
      <links />
      <button class="header__button" type="button">Рассказать историю</button>
    </div>
    <img class="header__menu" src="image/header-menu.svg" alt="меню" />
  </header>
</template>

<script>
import Links from '@/ui/Links';
export default {
  components: {
    links: Links,
  },
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1440px;
  margin: 0 auto;
  font-family: Inter, Arial, Helvetica, sans-serif;
}

.header__logo {
  max-width: 340px;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #121212;
  padding: 18px 0 18px 60px;
}

.header__menu-links {
  position: relative;
  display: flex;
  justify-content: space-between;
  list-style-type: none;
  padding-inline-start: 0;
  margin-block-start: 0;
  margin-block-end: 0;
  padding: 26px 60px;
}

.header__navigation {
  display: flex;
  justify-content: space-between;
}

.header__menu {
  display: none;
}

.header__button {
  border: none;
  background: none;
  text-decoration: none;
  display: inline-block;
  cursor: pointer;
  font-size: 18px;
  line-height: 24px;
  margin-right: 18px;
  color: #121212;
}

@media screen and (max-width: 768px) {
  .header__menu {
    display: block;
  }

  .header__menu-links {
    display: none;
  }
}
</style>
