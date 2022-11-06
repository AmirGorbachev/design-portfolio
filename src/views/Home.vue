<template lang="pug">
  .home
    Sidebar.home__sidebar
    ContentWrapper.home__content
</template>

<script>
// @ is an alias to /src
import Sidebar from '@/components/layouts/Sidebar.vue'
import ContentWrapper from '@/components/layouts/ContentWrapper.vue'

export default {
  name: 'Home',
  components: {
    Sidebar,
    ContentWrapper,
  },
}
</script>

<style scoped lang="scss">
.home {
  min-height: 100vh;
  display: grid;
  grid-auto-columns: 1fr;
  grid-template-columns: min-content 1fr;
  grid-template-rows: 1fr;
  gap: 0px 0px;
  grid-template-areas: 'sidebar content';

  &__sidebar {
    grid-area: sidebar;
  }

  &__content {
    grid-area: content;
  }
}
</style>
