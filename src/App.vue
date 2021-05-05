<template>
  <HelloWorld v-show="false" />
  <ThemeToggle />
  <Neummorphic />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";
import ThemeToggle from "./components/ThemeToggle.vue";
import Neummorphic from "./components/Neummorphic.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
    ThemeToggle,
    Neummorphic,
  },
});
</script>

<style lang="scss">
@import "../src/assets/app.scss";
</style>
