<template>
  <div class="bear-text">
    {{ bearText }}
  </div>
  <div class="toggleWrapper">
    <input
      type="checkbox"
      class="dn"
      id="dn"
    />
    <label
      for="dn"
      class="toggle"
    >
      <span class="toggle__handler"></span>
    </label>
    <div class="bear-body">
      <span class="eye left"></span>
      <span class="eye right"></span>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      bearText: "我是一隻可愛熊熊",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../styles/bear.scss";
</style>
