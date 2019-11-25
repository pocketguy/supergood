<template>
  <div class="container">
    <Logo />
    <h2>
      <a
        href="https://www.instagram.com/supergood.cafe"
        rel="noreferrer noopener nofollow"
        target="_blank"
        class="link"
      >
        @supergood.cafe
      </a>
    </h2>
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
  flex-direction: column
  .link
    font-family: 'Avenir Next'
    font-weight: 600
    font-style: normal
    font-size: 20px
    text-decoration: none
    color: black
    text-decoration: underline
    &:visited
      color: initial
</style>
