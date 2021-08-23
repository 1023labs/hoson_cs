<template>
  <v-app>
    <v-main>
      <v-container fill-height>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: '호손(주) - '
    }
  }
}
</script>
