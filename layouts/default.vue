<template>
  <v-app>
    <Header />
    <v-content>
      <v-container>
        <nuxt />
        <!-- <div v-if="this.$route.path == '/dashboard'">
          <p>ini Dashboard</p>
        </div> -->
        <!-- <Appointment v-if="this.$route.path == '/appointment'" /> -->
      </v-container>
    </v-content>
    <Footer />
  </v-app>
  <!-- <v-app v-else>
    <Login />
  </v-app> -->
</template>

<script>
// import Login from '../pages/Login/index.vue'
import Header from '../components/Header/index.vue'
import Footer from '../components/Footer/index.vue'
// import Appointment from '../pages/Appointment/index.vue'
// import Dashboard from '../pages/Dashboard/index.vue'

export default {
  components: {
    Header,
    Footer
    // Login
    // Appointment
    // Dashboard
  }
}
</script>
