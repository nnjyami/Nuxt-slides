<template>
  <div class="unit">
    <h3 class="sub-title">伝えたいこと</h3>
    <ul class="body">
      <li>
        CodeSandbox を使うと iOS でも<br />簡単にVue / Nuxt 素振り環境ができる！
      </li>
      <li>
        素振りの障壁を低くすることで、<br />より多くの人が素振りできるように
      </li>
      <li>
        CodeSandbox → Netlify へのデプロイが<br />追加されたことで、さらに可能性が！
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  layout: "slide",
  asyncData() {
    return {
      name: process.server ? "server" : "client"
    };
  }
};
</script>

<style scoped></style>
