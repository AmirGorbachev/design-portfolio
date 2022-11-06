<template lang="pug">
  .content-wrapper
    p Портфолио
</template>

<script>
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'ContentWrapper',
  components: {},
}
</script>

<style scoped lang="scss">
.content-wrapper {
  background: var(--light-color);
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
</style>
