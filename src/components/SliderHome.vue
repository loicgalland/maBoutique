<template>
  <v-card elevation="24" max-width="1000" class="mx-auto">
    <v-carousel hide-delimiters>
      <v-carousel-item
        v-for="(image, i) in images"
        :key="i"
        :src="image.src"
        cover
      ></v-carousel-item>
    </v-carousel>
  </v-card>
</template>

<script>
export default {
  name: "SliderHome",
  data() {
    return {
      images: [
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/sky.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/bird.jpg",
        },
        {
          src: "https://cdn.vuetifyjs.com/images/carousel/planet.jpg",
        },
      ],
    };
  },
};
</script>
