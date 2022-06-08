<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>

<template>
  <div class="home">
    <div
      class="image"
      alt="Vue logo"
      src="~@/assets/logo.png"/>
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<style lang="scss">
.image {
  height: 100px;
  background-image: url("@/assets/logo.png");
}
</style>
