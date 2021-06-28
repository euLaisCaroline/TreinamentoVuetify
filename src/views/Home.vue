<template>
  <v-card>
    <v-tollbar-title>Exercicios em Vuetify</v-tollbar-title>

    <Listen />
    <Carousel />
  </v-card>
</template>

<script>
import Listen from "@/components/Exercicio1/Listen";
import Carousel from "@/components/Exercicio2/Carousel";

export default {
  components: {
    Listen,
    Carousel,
  },
};
</script>
