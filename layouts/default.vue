<template>
  <v-app>
    <Header />
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <Footer />
  </v-app>
</template>

<script>
import Header from './Header/index.vue'
import Footer from './Nav_bottom/index.vue'

export default {
  components: {
    Header,
    Footer
  }
}
</script>
