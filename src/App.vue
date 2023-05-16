<template>
  <v-app>
    <v-main>
      <HelloWorld />
      <v-card class="mx-auto" width="400" prepend-icon="mdi-email">
        <v-card-text> Coucou à tous </v-card-text>
      </v-card>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
