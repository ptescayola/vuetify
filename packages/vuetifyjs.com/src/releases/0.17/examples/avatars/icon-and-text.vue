<template>
  <v-layout wrap justify-space-around align-center>
    <v-avatar class="indigo">
      <v-icon dark>account_circle</v-icon>
    </v-avatar>
    <v-avatar>
      <img src="https://cdn.vuetifyjs.com/images/john.jpg" alt="John">
    </v-avatar>
    <v-badge overlap color="red">
      <span slot="badge">3</span>
      <v-avatar
        class="purple"
      >
        <v-icon dark>notifications</v-icon>
      </v-avatar>
    </v-badge>
    <v-avatar class="teal">
      <span class="white--text headline">C</span>
    </v-avatar>
    <v-avatar class="red">
      <span class="white--text headline">J</span>
    </v-avatar>
  </v-layout>
</template>
