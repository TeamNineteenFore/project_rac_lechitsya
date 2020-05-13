<template>
  <header class="header page__header">
    <h1 class="header__logo">
      Проект Благотворительного Фонда Константина Хабенского
    </h1>
    <nav class="header__navigation">
      <ul class="header__menu-links">
        <li>
          <a href="#" class="header__link header__link_active" target="_blank"
            >Главная</a
          >
        </li>
        <li><a href="#" class="header__link" target="_blank">Истории</a></li>
        <li>
          <a href="#" class="header__link" target="_blank"
            >Рассказать историю</a
          >
        </li>
      </ul>
      <img class="header__menu" src="image/header-menu.svg" alt="меню" />
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
.page__header {
  margin: 18px 60px;
  font-family: Inter, Arial, Helvetica, sans-serif;
}

@media screen and (max-width: 1280px) {
  .page__header {
    margin: 18px 50px;
  }
}

.header {
  position: relative;
  display: flex;
  justify-content: space-between;
  max-width: 1320px;
  align-items: center;
}

.header__logo {
  width: 340px;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #121212;
}

.header__menu-links {
  position: relative;
  display: flex;
  justify-content: space-between;
  list-style-type: none;
  padding-inline-start: 0;
  margin-block-start: 0;
  margin-block-end: 0;
}

.header__link {
  text-decoration: none;
  font-size: 18px;
  line-height: 24px;
  margin-right: 18px;
  color: #121212;
}

.header__link_active {
  text-decoration-line: underline;
}

.header__menu {
  display: none;
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
