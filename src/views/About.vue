<template>
  <div>
    <AboutPage />
    <Footer />
  </div>
</template>

<script>
import AboutPage from '@/components/AboutPage.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'about',
  components: {
    AboutPage,
    Footer
  }
}
</script>