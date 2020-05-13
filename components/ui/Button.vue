<template>
  <button class="button">
    <slot></slot>
  </button>
</template>

<script>
export default {};
</script>

<style scoped>
.button {
  background-color: #fbfbfb;
  border: none;
  max-width: 280px;
  width: 100%;
  height: 82px;
}
</style>
