<template lang="pug">
  section.portfolio
    .sectiontitle Портфолио

    v-layout(row wrap)
      v-flex(lg4 md4 xs6)
        .img-container
          a(href='#')
            .img-container__picture
        .box
          .timeline__category Начальник отдела мониторинга сети
          .timeline__name ООО "РегионТелеком"
          p.
            Lorem ipsum dolor sit amet, in quodsi vulputate pro. Ius illum vocent mediocritatem an, cule dicta iriure at. Ubique maluisset vel te, his dico vituperata ut. Pro ei phaedrum maluisset. Ex audire suavitate has, ei quodsi tacimates sapientem sed, pri zril ubique ut. Lorem ipsum dolor sit amet, in quodsi.
      v-flex(lg4 md4 xs6)
        .img-container
          a(href='#')
            .img-container__picture
        .box
          .timeline__category Начальник отдела мониторинга сети
          .timeline__name ООО "РегионТелеком"
          p.
            Lorem ipsum dolor sit amet, in quodsi vulputate pro. Ius illum vocent mediocritatem an, cule dicta iriure at. Ubique maluisset vel te, his dico vituperata ut. Pro ei phaedrum maluisset. Ex audire suavitate has, ei quodsi tacimates sapientem sed, pri zril ubique ut. Lorem ipsum dolor sit amet, in quodsi.
      v-flex(lg4 md4 xs6)
        .img-container
          a(href='#')
            .img-container__picture
        .box
          .timeline__category Начальник отдела мониторинга сети
          .timeline__name ООО "РегионТелеком"
          p.
            Lorem ipsum dolor sit amet, in quodsi vulputate pro. Ius illum vocent mediocritatem an, cule dicta iriure at. Ubique maluisset vel te, his dico vituperata ut. Pro ei phaedrum maluisset. Ex audire suavitate has, ei quodsi tacimates sapientem sed, pri zril ubique ut. Lorem ipsum dolor sit amet, in quodsi.


      v-flex(lg4 md4 xs6)
        .img-container
          a(href='#')
            .img-container__picture
        .box
          .timeline__category Начальник отдела мониторинга сети
          .timeline__name ООО "РегионТелеком"
          p.
            Lorem ipsum dolor sit amet, in quodsi vulputate pro. Ius illum vocent mediocritatem an, cule dicta iriure at. Ubique maluisset vel te, his dico vituperata ut. Pro ei phaedrum maluisset. Ex audire suavitate has, ei quodsi tacimates sapientem sed, pri zril ubique ut. Lorem ipsum dolor sit amet, in quodsi.
      v-flex(lg4 md4 xs6)
        .img-container
          a(href='#')
            .img-container__picture
        .box
          .timeline__category Начальник отдела мониторинга сети
          .timeline__name ООО "РегионТелеком"
          p.
            Lorem ipsum dolor sit amet, in quodsi vulputate pro. Ius illum vocent mediocritatem an, cule dicta iriure at. Ubique maluisset vel te, his dico vituperata ut. Pro ei phaedrum maluisset. Ex audire suavitate has, ei quodsi tacimates sapientem sed, pri zril ubique ut. Lorem ipsum dolor sit amet, in quodsi.
      v-flex(lg4 md4 xs6)
        .img-container
          a(href='#')
            .img-container__picture
        .box
          .timeline__category Начальник отдела мониторинга сети
          .timeline__name ООО "РегионТелеком"
          p.
            Lorem ipsum dolor sit amet, in quodsi vulputate pro. Ius illum vocent mediocritatem an, cule dicta iriure at. Ubique maluisset vel te, his dico vituperata ut. Pro ei phaedrum maluisset. Ex audire suavitate has, ei quodsi tacimates sapientem sed, pri zril ubique ut. Lorem ipsum dolor sit amet, in quodsi.

</template>

<script>
export default {
  name: 'portfolio'
}
</script>

<style lang="stylus">
.img-container
  position relative
  overflow hidden
  height 300px

  a:before
    content ''
    position absolute
    left 0
    top 0
    display block
    width 100%
    height 100%
    background-color #fefefe
    opacity 0
    z-index 2
    transition all

  &__picture
    position relative
    width 100%
    height 100%
    transform scale(1, 1)
    transition all .4s ease 0s
    background url('http://kvant.space/sites/default/files/yupiter3_0.jpg')
    background-position 50% 50%
    background-repeat no-repeat
    background-size cover

.portfolio
  .flex
    &:hover
      .img-container__picture
        transform scale(1.1, 1.1)
      a:before
        opacity .3
</style>
