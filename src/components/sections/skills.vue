<template lang="pug">
section.skills
  v-app
    .skills__title Навыки
    v-layout(row wrap)
      v-flex(xs6)
        .skills__box
          .skills__subtitle
            .skills__icon: v-icon(large dark) settings
            .skills__name Навыки
          .skills__bars
            ul
              li
                span.label {{ex1.label}}
                v-slider(v-model="ex1.val"
                        :color="ex1.color")
              li
                span.label {{ex2.label}}
                v-slider(v-model="ex2.val"
                          :color="ex2.color")
              li
                span.label {{ex3.label}}
                v-slider(v-model="ex3.val"
                            :color="ex3.color")
              li
                span.label {{ex4.label}}
                v-slider(v-model="ex4.val"
                            :color="ex4.color")
              li
                span.label {{ex1.label}}
                v-slider(v-model="ex1.val"
                            :color="ex1.color")
              li
                span.label {{ex2.label}}
                v-slider(v-model="ex2.val"
                            :color="ex2.color")

      v-flex(xs6)
        .skills__box
          .skills__subtitle
            .skills__icon: v-icon(large dark) person
            .skills__name Качества
          .skills__bars
            ul
              li
                span.label {{ex1.label}}
                v-slider(v-model="ex1.val"
                        :color="ex1.color")
              li
                span.label {{ex2.label}}
                v-slider(v-model="ex2.val"
                          :color="ex2.color")
              li
                span.label {{ex3.label}}
                v-slider(v-model="ex3.val"
                            :color="ex3.color")
              li
                span.label {{ex4.label}}
                v-slider(v-model="ex4.val"
                            :color="ex4.color")
              li
                span.label {{ex1.label}}
                v-slider(v-model="ex1.val"
                            :color="ex1.color")
              li
                span.label {{ex2.label}}
                v-slider(v-model="ex2.val"
                            :color="ex2.color")
</template>

<script>
export default {
  name: 'skills',
  data () {
    return {
      ex1: { label: 'css', val: 25, color: 'orange darken-3' },
      ex2: { label: 'html', val: 75, color: 'green lighten-1' },
      ex3: { label: 'javascript', val: 50, color: 'red' },
      ex4: { label: 'vuejs', val: 50, color: 'red' }
    }
  }
}
</script>

<style lang="stylus">
.skills
  &__title
    position relative
    height 70px
    text-align center
    font-size 36px
    font-weight 100
    line-height 20px
  &__box
    padding 25px
    position: relative
    background: #fefefe
    -moz-border-radius: 2px
    -webkit-border-radius: 2px
    -khtml-border-radius: 2px
    border-radius: 2px

    -moz-box-shadow: 0 1px 4px 0 rgba(0, 0, 0, .14)
    -webkit-box-shadow: 0 1px 4px 0 rgba(0, 0, 0, .14)
    -khtml-box-shadow: 0 1px 4px 0 rgba(0, 0, 0, .14)
    box-shadow: 0 1px 4px 0 rgba(0, 0, 0, .14)

  &__subtitle
    position relative
    margin-top -57px
    text-align center

  &__icon
    margin 0 auto
    position relative
    display inline-block
    overflow hidden
    background-color #304fff
    color #fefefe
    border-radius 50%
    box-shadow 0 6px 10px rgba(0, 0, 0, .2)
    transition all .2s ease 0s

    i
      width 62px
      height 62px

  &__name
    margin 15px 0
    display block
    font-weight 400
    font-size 17px

  li
    padding 0
    border-bottom none

  .label
    color #363636
    text-transform uppercase
  div[role="slider"].input-group
    padding 0

    &__input
      position relative
      top -10px
    .input-group__details
      display none
      background-color pink

.application
  &--light
    background-color transparent

</style>
