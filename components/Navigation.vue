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
      Pages: [
        "about",
        "aboutMe",
        "equipment",
        "whyiOS",
        "onlineIDE",
        "iOSKeyboardBug",
        "codeSandbox",
        "iOS122PWA",
        "iOSProblem",
        "codeSandboxNetlify",
        "codeSandboxToNetlify",
        "summary"
      ]
    };
  }
};
</script>

<style scoped>
.nav {
  font-size: 0.7em;
  width: 96vw;
  height: 3vh;
  line-height: 3vh;

  display: flex;
  flex-direction: row-reverse;
  justify-content: center;

  position: fixed;
  bottom: 5vh;
  left: 2vw;
  z-index: 100;
}
</style>
