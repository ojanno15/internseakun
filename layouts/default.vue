<template>
  <div>
    <Navbar/>
    <Nuxt />
    <Footer/>
  </div>
</template>
<script>
import Navbar from "~/components/Mollecules/Navbar.vue"
import Footer from "~/components/Mollecules/Footer.vue"
export default {
  components: {
    Navbar: Navbar,
    Footer: Footer,
  }
}
</script>
<style>
</style>