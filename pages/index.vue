<template>
  <div class="container">
    <Logo />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  components: {
    Logo
  }
}
</script>

<style lang="sass" scoped>
.container
  min-height: 100vh
  display: flex
  align-items: center
  justify-content: center
</style>
