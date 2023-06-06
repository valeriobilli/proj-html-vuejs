<script>
import PageHeader from './components/PageHeader.vue'
import PageMain from './components/PageMain.vue'
import PageFooter from './components/PageFooter.vue'


export default {
  components: {
    PageHeader,
    PageMain,
    PageFooter
  },

  data() {
    return {
      navLinks: [
        "Home",
        "About",
        "Academics",
        "Courses",
        "News"
      ]
    }
  }
}


</script>

<template>
  <header>
    <PageHeader :navLinks="navLinks" />
  </header>

  <main>
    <PageMain />
  </main>

  <footer>
    <PageFooter />
  </footer>
</template>

<style scoped></style>
