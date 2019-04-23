<template>
  <section>
    <div>
      <h1 class="subtitle">
        iOS で Vue 環境を作るための旅に出たら<br />
        JAMStack な登壇資料ができて<br />
        平成最後の登壇をしている話
      </h1>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green"
          >Documentation <IconLink
        /></a>
        <NLink to="/about" class="button--grey">About</NLink>
      </div>
    </div>
  </section>
</template>

<script>
import IconLink from "~/components/IconLink.vue";

export default {
  components: {
    IconLink
  }
};
</script>

<style scoped>
.green {
  color: #00c48d;
}

.subtitle {
  font-size: 1.4em;
  color: #2e495e;
  padding-bottom: 0px;
  writing-mode: vertical-rl;
  font-family: heisei-mincho-stdn, serif;
  font-feature-settings: "palt";
  letter-spacing: 0.12em;
}

.links {
  padding-top: 15px;
}
</style>
