<template lang="pug">
  .sidebar
    .sidebar__wrapper
      p Портфолио
      nav.sidebar__nav
        ul.sidebar__nav-wrapper
          li.sidebar__item Обо мне
          li.sidebar__item Работы
          li.sidebar__item Контакты
</template>

<script>
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Sidebar',
  components: {},
}
</script>

<style scoped lang="scss">
.sidebar {
  background: var(--light-color);
  height: 100%;

  &__wrapper {
    padding: 40px 60px;
  }

  &__nav {
    margin-top: 50px;
  }

  &__nav-wrapper {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }

  &__item {
    cursor: pointer;
  }
}
</style>
