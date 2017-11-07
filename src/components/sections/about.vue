<template lang="pug">
  section.about
    .box
        v-layout(row wrap)
          v-flex(xs5)
            .about__photo
              img(src="../../../static/about__photo.jpg")
            .about__info
              ul
                li Место жительства_ico: г.Иркутск, Россия
                li Телефон_ico: 89500883135
                li email_ico: egormad@gmail.com

          v-flex(xs7)
            .about__person
              .about__title Егор Мадьяров
              .about__subtitle Front-end Developer
              .about__social
                a.about__btn: v-icon ac_unit
                a.about__btn: v-icon account_balance
                a.about__btn: v-icon account_balance
                a.about__btn: v-icon account_balance
                a.about__btn: v-icon account_balance
            .about__description
              p.
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque.
              p.
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque.
              p.
                Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores.
</template>

<script>
export default {
  name: 'about'

}
</script>

<style lang="stylus">
.about
  &__photo
    margin-bottom 15px
    img
      max-width 100%
      height auto
  &__info
    background pink

  &__person
    text-align left
  &__title
    font-size 42px
    font-weight 100
    line-height 44px
  &__subtitle
    margin-top 15px
    font-size 16px
    font-weight 400
  &__social
    margin 25px 0

  &__btn
    position relative
    margin-right 20px
    display inline-block
    vertical-align top
    overflow hidden
    width 40px
    height 40px
    line-height 37px
    text-align center
    background-color #304fff
    color #fefefe
    font-size 21px

    box-shadow 0 6px 10px 0 rgba(0, 0, 0, .2)

    transition all .2s ease 0s

    border-radius 52px

  &__description
    text-align left
    font-size 16px
    line-height 25px
    color #363636
    p
      margin-bottom 15px

</style>
