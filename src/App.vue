<template>
  <TheHeader />
  <RouterView />
  <Footer />
</template>

<script>
import TheHeader from '~/components/TheHeader'
import Footer from '~/components/Footer'

export default {
  components: {
    TheHeader,
    Footer
  }
}
</script>

<style lang="scss">
  @import "~/scss/main.scss";
</style>
