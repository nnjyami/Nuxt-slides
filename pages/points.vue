<template>
  <div class="container">
    <div class="heiseiText">
      <h1>伝えたいこと</h1>
      <ul>
        <li>
          CodeSandbox を使うと iOS でも簡単にVue / Nuxt 素振り環境ができる！
        </li>
        <li>素振りの障壁を低くすることで、より多くの人が素振りできるように</li>
        <li>
          CodeSandbox → Netlify へのデプロイが追加されたことで、さらに可能性が！
        </li>
      </ul>
      <p><NLink to="/" class="button--grey">Back home</NLink></p>
    </div>
  </div>
</template>

<script>
export default {
  asyncData() {
    return {
      name: process.server ? "server" : "client"
    };
  }
};
</script>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.heiseiText {
  writing-mode: vertical-rl;
  font-family: heisei-mincho-stdn, serif;
  font-feature-settings: "palt";
  letter-spacing: 0.12em;
  text-align: left;
}
h1 {
  font-weight: 400;
}
.name {
  color: #00c48d;
}
p {
  margin-top: 20px;
}
</style>
