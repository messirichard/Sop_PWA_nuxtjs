<template>
  <v-bottom-navigation>
    <v-btn value="appointment" to="/appointment">
      <span>Appointment</span>
      <v-icon>mdi-history</v-icon>
    </v-btn>

    <v-btn value="termination" to="/termination">
      <span>Termination</span>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn value="distributor" to="/distribution">
      <span>Distributor</span>
      <v-icon>mdi-map-marker</v-icon>
    </v-btn>

    <v-btn value="video" to="/video">
      <span>Video</span>
      <v-icon>mdi-video</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import '../../assets/sass/Footer.scss';
</style>
