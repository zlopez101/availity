<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <a href="/login"><v-btn>
      <v-icon>mdi-account</v-icon>
    </v-btn></a>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
