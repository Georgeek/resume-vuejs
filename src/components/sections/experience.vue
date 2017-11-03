<template lang="pug">
  section.experience
    .experience__title Опыт работы
      v-icon(x-large) work
    .timeline
      .timline__block
        .timeline__point
        .timeline__content
</template>

<script>
export default {
  name: 'experience'
}
</script>

<style lang="stylus">
.experience
  &__title
    position relative
    height 70px
    text-align center
    font-size 36px
    font-weight 100
    line-height 20px
</style>
