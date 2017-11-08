<template lang="pug">
  section.contactme
    .sectiontitle Пригласите на собеседование

    v-layout(row wrap)
      v-flex(xs6 offset-xs3)
        .box
          .about__info
            ul
              li Место жительства_ico: г.Иркутск, Россия
              li Телефон_ico: 89500883135
              li email_ico: egormad@gmail.com
          .about__photo
            img(src="../../../static/about__photo.jpg")
</template>

<script>
export default {
  name: 'contactme'
}
</script>

<style lang="stylus">

</style>
