<template>
  <img
    src="../src/assets/forest.jpg"
    style="height: 100vh; width: 100%"
  >
  <div class="container">
    <BearComponent />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import BearComponent from "./components/BearComponent.vue";

@Options({
  components: {
    BearComponent,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
body {
  background-color: #658397;
  overflow: hidden;
}
</style>
