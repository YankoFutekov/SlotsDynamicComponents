<template>
  <div>
    <div class="title">
      <slot name="title"></slot>
      <span style="color: green">
        <slot name="subtitle">The subtitle</slot>
      </span>
    </div>
    <div class="content">
      <slot name="content"></slot>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
div {
  border: 1px solid #ccc;
  box-shadow: 1px 1px 2px black;
  padding: 30px;
  margin: 30px auto;
  text-align: center;
}
.title {
  font-weight: bold;
}
</style>
