<template>
  <v-app>
    <v-toolbar app flat height="80" color="#fff">
      <v-toolbar-title class="title">
        d<span class="home">home</span>stique
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-icon color="#FF8C00">local_phone</v-icon>
      <span class="phone-number small-screen"><a href="tel:+3358869590">06 58 86 95 90</a></span>
      <span class="phone-number big-screen">06 58 86 95 90</span>
    </v-toolbar>
    <v-content>
      <v-container fluid>
        <nuxt/>
      </v-container>
    </v-content>
    <v-footer class="justify-center" color="#fff">
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<style lang="scss" scoped>
.container {
  padding: 0;
  min-width: 300px;
}
.title {
  text-transform: uppercase;
  font-size: 24px !important;
  .home {
    color: #ff8c00;
  }
  @media (max-width: 374px) {
    font-size: 22px !important;
  }
}
.phone-number {
  font-size: 22px;
  margin-left: 5px;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
  width: auto;
  @media (max-width: 374px) {
    font-size: 16px;
  }
}
 @media (max-width: 1024px) {
    .big-screen {
      display: none;
    }
    a[href^="tel:"] {
    color: #000;
    text-decoration: none;
    }
  }
    @media (min-width: 1025px) {
    .small-screen {
      display: none;
    }
  }
</style>

