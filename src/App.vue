<template>
  <NavMenu />
  <SliderHome />
</template>

<script>
import NavMenu from "./components/Menu.vue";
import SliderHome from "./components/SliderHome.vue";
export default {
  name: "App",
  components: {
    NavMenu,
    SliderHome,
  },
};
</script>
