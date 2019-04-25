<template>
  <div class="container">
    <Nuxt />
    <navigation />
  </div>
</template>

<script>
import Navigation from "~/components/Navigation.vue";

export default {
  components: {
    Navigation
  }
};
</script>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  color: #2e495e;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.container {
  max-height: 93vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  position: relative;
  flex-direction: column;
  margin-top: 6vh;
}
.unit {
  max-height: 80vh;
  font-family: heisei-mincho-stdn, serif;
  font-feature-settings: "palt";
  letter-spacing: 0.12em;
  line-height: 2;
  text-align: left;

  writing-mode: vertical-rl;
}
.sub-title,
.body {
  display: inline-block;
  height: 100%;
}
.sub-title {
  font-size: 2.4em;
  margin-left: 2.4em;
}
.body {
  font-size: 1.8em;
  margin-left: 2em;
}
ul li {
  margin-left: 1.5em;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #00c48d;
  color: #00c48d;
  text-decoration: none;
  padding: 0 8px;
  display: inline-flex;
  align-self: center;
}

.button--green:hover {
  color: #fff;
  background-color: #00c48d;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #2e495e;
  color: #2e495e;
  text-decoration: none;
  padding: 0 14px;
  margin-left: 10px;
}

.button--grey:hover {
  color: #fff;
  background-color: #2e495e;
}
</style>
