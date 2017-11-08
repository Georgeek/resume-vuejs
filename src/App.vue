<template>
  <div id="app">
    <Resume/>
  </div>
</template>

<script>
import Resume from './components/Resume'

export default {
  name: 'app',
  components: {
    Resume
  }
}
</script>

<style lang="stylus">
@import '../node_modules/normalize.css/normalize.css'
@import '../node_modules/vuetify/dist/vuetify.min.css'

@import './assets/styles/*.styl'

#app
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
</style>
