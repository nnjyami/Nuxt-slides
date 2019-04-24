<template>
  <div class="unit">
    <h3 class="sub-title">iOS<br />外付けキーボードの矢印問題</h3>
    <p class="body">
      iOS の外付けキーボードは<br />テキストエリアやインプット要素以外では<br />
      矢印キーのキーイベントが発生しないバグがある。<br />
      フロントの実装の仕方によって、矢印キーが使えない！
    </p>
    <p class="body">
      先程挙げた Online IDE の中では CodeSandbox だけは矢印キーが使えた！
    </p>
  </div>
</template>

<script>
export default {
  layout: "slide"
};
</script>

<style scoped></style>
