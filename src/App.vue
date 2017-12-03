<template>
  <v-app light>
    <v-navigation-drawer v-model="sideNav">

    </v-navigation-drawer>
    <v-toolbar>
      <v-toolbar-side-icon @click.native="sideNav = !sideNav"></v-toolbar-side-icon>
      <v-toolbar-title>K-Meetup</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-item>
        <v-icon left>supervisor_account</v-icon>
        <v-btn flat>Vew Meetups</v-btn>
      </v-toolbar-item>
    </v-toolbar>
    <main>

    </main>
  </v-app>
</template>

<script>
  export default {
    data () {
      return {
        sideNav: false
      }
    }
  }
</script>
