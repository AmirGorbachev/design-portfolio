<template lang="pug">
  .sidebar
    p Кристина
    nav.sidebar__nav
      ul.sidebar__nav-wrapper
        li.sidebar__nav-item Обо мне
        li.sidebar__nav-item Работы
        li.sidebar__nav-item Контакты
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
  &__nav {
  }
  &__nav-wrapper {
  }
  &__nav-item {
  }
}
</style>
