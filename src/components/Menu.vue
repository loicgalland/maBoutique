<template>
  <div class="d-flex ma-3">
    <v-toolbar title="MaBoutique">
      <v-toolbar-items>
        <v-btn>
          <a href="#" class="text-decoration-none"> Home </a>
        </v-btn>
      </v-toolbar-items>
      <v-toolbar-items>
        <v-btn>
          <a href="#" class="text-decoration-none color-text-black">
            Nous contacter
          </a>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </div>
</template>

<script>
export default {
  name: "NavMenu",
  data: () => ({
    items: [{ title: "Home" }, { title: "Nous contacter" }],
  }),
};
</script>
