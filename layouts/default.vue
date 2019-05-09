<template>
  <v-app>
  <v-toolbar app flat height="80" color="#f6f1eb">
    <v-toolbar-title class="title">d<span class="home">home</span>stique</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-icon>local_phone</v-icon>
    <span class="phone-number">06 58 86 95 90</span>
  </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer
      class="justify-center"
      color="#f6f1eb"
      fixed
      app
    >
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<style lang="scss" scoped>
  .title {
    text-transform: uppercase;
    font-size: 24px !important;
    .home {
      color: #FF8C00;
    }
  }
  .phone-number {
    font-size: 20px;
    margin-left: 5px;
  }
</style>

