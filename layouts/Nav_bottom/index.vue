<template>
  <v-bottom-navigation v-model="bottomNav">
    <v-btn value="appointment">
      <span>Appointment</span>
      <v-icon>mdi-history</v-icon>
    </v-btn>

    <v-btn value="termination">
      <span>Termination</span>
      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn value="distributor">
      <span>Distributor</span>
      <v-icon>mdi-map-marker</v-icon>
    </v-btn>

    <v-btn value="nearby">
      <span>Nearby</span>
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
