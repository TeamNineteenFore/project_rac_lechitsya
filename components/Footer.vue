<template>
  <section class="footer footer_indent">
    <div class="footer__main">
      <h3 class="footer__thanks">
        Спасибо всем, кто помог состояться этому проекту
      </h3>
      <ul class="footer__nav footer__in-links">
        <li class="footer__nav-item footer__nav-item_line">
          <a href="#" class="footer__local-link">Главная</a>
        </li>
        <li class="footer__nav-item footer__nav-item_line">
          <a href="#" class="footer__local-link">Истории</a>
        </li>
      </ul>
      <ul class="footer__nav footer__out-links">
        <li class="footer__nav-item footer__nav-item_turn">
          <a href="#" class="footer__local-link">Мы в Инстаграме и Youtube</a>
        </li>
        <li class="footer__nav-item footer__nav-item_turn">
          <a href="#" class="footer__local-link footer__local-link_color"
            >Поделитесь ↗</a
          >
        </li>
      </ul>
    </div>
    <div class="footer__bottom">
      <p class="footer__last">Рак Лечится 2020</p>
      <p class="footer__last">Сделано студентами Яндекс Практикум</p>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background-color: #fbfbfb;
  max-width: 1440px;
  /* выше установили ограничение по максимальной ширине */
  width: 100%;
  max-height: 356px;
}

.footer__bottom {
  margin: 0 60px 60px 60px;
  display: flex;
  position: relative;
  justify-content: space-between;
}

.footer__in-links {
  padding-left: 0;
  margin: 0 auto 0 -70px;
}

.footer__last {
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 1;
  /* identical to box height, or 100% */
  color: #898989;
}

.footer__local-link {
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 1.33;
  /* identical to box height, or 133% */
  color: #000000;
  text-decoration: none;
}

.footer__local-link_color {
  color: #121212;
}

.footer__main {
  margin: 65px 60px 90px 60px;
  display: flex;
  position: relative;
  justify-content: space-between;
}

.footer__nav-item {
  list-style: none;
  padding-right: 30px;
  margin-right: 0;
}

.footer__nav-item_line {
  display: inline; /* Отображать как строчный элемент */
}

.footer__nav-item:last-of-type {
  padding-right: 0;
}

.footer__nav-item_turn {
  display: block;
  margin-bottom: 44px;
}

.footer__nav-item_turn:last-of-type {
  margin-bottom: 0;
}

.footer__nav {
  padding-right: auto;
  text-align: left;
}

.footer__out-links {
  padding: 0;
  margin: 0 0 auto auto;
  width: 300px;
}

.footer__thanks {
  max-width: 340px;
  font-family: Inter, Arial, sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 32px;
  line-height: 1.12;
  /* or 112% */
  color: #000000;
  margin: 0 auto auto 0;
}

.footer_indent {
  padding: 0;
  margin: 0 auto;
}
</style>
