<template lang="pug">
  .home
    Sidebar.home__sidebar
    ContentWrapper.home__content
</template>

<script>
// @ is an alias to /src
import Sidebar from '@/components/Sidebar.vue'
import ContentWrapper from '@/components/ContentWrapper.vue'

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
  display: grid;
  grid-auto-columns: 1fr;
  grid-template-columns: 20% 80%;
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
