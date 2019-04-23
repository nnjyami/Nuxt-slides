<template>
  <section>
    <div>
      <Logo :width="50" />
      <h2 class="subtitle">iOS でもできる最高の素振り環境</h2>
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
import Logo from "~/components/Logo.vue";
import IconLink from "~/components/IconLink.vue";

export default {
  components: {
    Logo,
    IconLink
  }
};
</script>

<style scoped>
.green {
  color: #00c48d;
}

.subtitle {
  font-weight: 300;
  font-size: 1.4em;
  color: #2e495e;
  padding-bottom: 15px;
  writing-mode: vertical-rl;
  font-family: heisei-mincho-stdn, serif;
  font-feature-settings: "palt";
  letter-spacing: 0.8em;
}

.links {
  padding-top: 15px;
}
</style>
