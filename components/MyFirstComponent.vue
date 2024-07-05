<template>
  <v-card
    variant="outlined"
    color="white"
    class="mx-auto mb-2"
    max-width="344"
    >
  <v-card-title class="text-center"> {{ teamOne}} vs. {{ teamTwo }}</v-card-title>
  <v-card-text class="text-center" > {{ matchDate }} <br> {{ matchLocation }}</v-card-text>

  </v-card>
</template>

<style></style>

<script setup>
const props = defineProps(["teamOne", "teamTwo", "matchDate", "matchLocation"]);
</script>



