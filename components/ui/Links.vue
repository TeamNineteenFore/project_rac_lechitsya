<template>
  <nav class="menu">
    <a href="#" class="menu__link menu__link_active" target="_blank">Главная</a>
    <a href="#" class="menu__link" target="_blank">Истории</a>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.menu__link {
  text-decoration: none;
  font-size: 18px;
  line-height: 24px;
  margin-right: 18px;
  color: #121212;
}

.menu__link_active {
  text-decoration-line: underline;
}
</style>
