<template>
  <div class="link">
    {{ nav }}
  </div>
</template>

<script>
import PageIndex from "~/assets/page_index";
export default {
  asyncData(context) {
    const nav = PageIndex.map(
      (v, k) => `<NLink to="/{{v}}" class="button--grey">{{k}}</NLink>`
    );
    return {
      nav: nav
    };
  }
};
</script>
