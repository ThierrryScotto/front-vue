<template>
  <v-app>
    <v-app-bar
      app
      dark
      color="primary"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://www.grupoa.com.br/hs-fs/hubfs/logo-grupoa.png?width=136&name=logo-grupoa.png"
          transition="scale-transition"
          width="130"
        />

      <v-chip
        class="ma-2"
        color="primary"
        href="/"
        medium
      >
        Alunos  
      </v-chip>

      </div>
    </v-app-bar>
    <v-content>
      <router-view />
    </v-content>
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
