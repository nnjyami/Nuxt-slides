<template>
  <section>
    <div>
      <h1 class="subtitle">
        iOS だけで Vue が書ける環境を作り<br />
        Netlify へデプロイして<br />
        JAMStack な LT をする話
      </h1>
      <Navigation />
    </div>
  </section>
</template>

<script>
import IconLink from "~/components/IconLink.vue";
import Navigation from "~/components/Navigation.vue";

export default {
  components: {
    IconLink,
    Navigation
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
  text-align: left;
}

.links {
  padding-top: 15px;
}
</style>
