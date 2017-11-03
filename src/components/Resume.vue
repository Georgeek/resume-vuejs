<template>
  <div class="container">
    <div class="wrapper">
      <about />
      <skills />
      <experience />
    </div>
  </div>
</template>

<script>
import about from './sections/about'
import skills from './sections/skills'
import experience from './sections/experience'

export default {
  name: 'Resume',
  components: {
    about,
    skills,
    experience
  }
}
</script>

<style lang="sass">

</style>
