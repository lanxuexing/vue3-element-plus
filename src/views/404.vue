<template>
  <div class="not-found">
    <img src="@/assets/404.gif" alt="404" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "404",
  components: {},
});
</script>

<style scoped>
.not-found {
  width: 100%;
  height: 100%;
  overflow: hidden;
}
.not-found img {
  width: 100%;
  height: 100%;
}
</style>