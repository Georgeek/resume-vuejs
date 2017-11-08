<template>
  <div class="container">
    <div class="wrapper">
      <about />
      <skills />
      <experience />
      <services />
      <education />
      <portfolio />
      <contactme />
    </div>
  </div>
</template>

<script>
import about from './sections/about'
import skills from './sections/skills'
import experience from './sections/experience'
import services from './sections/services'
import education from './sections/education'
import portfolio from './sections/portfolio'
import contactme from './sections/contactme'

export default {
  name: 'Resume',
  components: {
    about,
    skills,
    experience,
    services,
    education,
    portfolio,
    contactme
  }
}
</script>

<style lang="sass">

</style>
