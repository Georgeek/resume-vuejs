<template lang="pug">
section.skills
  v-app#sliderjs
    .sectiontitle Навыки
    v-layout(row wrap)
      v-flex(xs6)
        .box
          .subtitle
            .subtitle__icon: v-icon(large dark) settings
            .subtitle__name Навыки
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
        .box
          .subtitle
            .subtitle__icon: v-icon(large dark) person
            .subtitle__name Качества
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
