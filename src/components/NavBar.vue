<template>
  <v-app-bar app color="gray" light flat class="px-10">
    <!-- <v-btn icon>
      <v-icon color="#A7121D">fas fa-dragon</v-icon>  
    </v-btn> -->
    <div class="navbar__logo">
      <img src="../assets/logo.svg" alt="website logo" />
    </div>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Work</v-btn>
    <v-btn text @click="scroll('about')">About</v-btn>
    <v-btn text @click="scroll('project')">Resume</v-btn>
    <v-btn text @click="scroll('contact')"> Contact</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style></style>
