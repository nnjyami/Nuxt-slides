<template>
  <div class="nav">
    <NLink
      v-for="(page, key) in Pages"
      :key="`${key}`"
      :to="`/${page}`"
      class="button--grey"
      >{{ key }}</NLink
    >
  </div>
</template>

<script>
// import PageIndex from "~/assets/page_index";
export default {
  data() {
    return {
      Pages: ["about", "points", "equipment"]
    };
  }
};
</script>

<style scoped>
.nav {
  font-size: 0.8em;
  width: 96vw;
  position: absolute;
  bottom: 0.5vh;
  left: 2vw;
  z-index: 100;
}
</style>
