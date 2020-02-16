<template>
  <div class="main-page">
    <header-line></header-line>
    <top-banner></top-banner>
    <about></about>
    <faq></faq>
    <comments></comments>
    <footer-registration></footer-registration>
    <header-line></header-line>
  </div>
</template>

<script>
import HeaderLine from '~/components/HeaderLine.vue'
import TopBanner from '~/components/TopBanner.vue'
import About from '~/components/About.vue'
import Faq from '~/components/Faq.vue'
import Comments from '~/components/Comments.vue'
import FooterRegistration from '~/components/FooterRegistration.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    HeaderLine,
    TopBanner,
    About,
    Faq,
    Comments,
    FooterRegistration,
    Footer,
  },
  head: {
    link: [
      { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Roboto&display=swap' }
    ]
  }
}
</script>

<style>

</style>
