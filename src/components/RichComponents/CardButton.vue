<template>
  <a class="card-button" target="_blank" rel="noopener noreferrer" :href="uri">
    <i aria-hidden="true" class="material-icons card-button-icon">arrow_forward</i>
    <span class="card-button-title">{{title}}</span>
  </a>
</template>

<style lang="scss" scoped>
.card-button {
  text-decoration: none;
  line-height: 24px;
  color:#4285f4;
  border: 1px solid#e5e5e5;
  border-radius: 40px;
  display: block;
  font-weight: 500;
  padding: 8px 16px;
  text-align: center;
  position: relative;
  margin-top: 16px;
}
.card-button-icon {
  left: 0;
  margin-left: 12px;
  position: absolute;
}
</style>

<script>
export default {
  name: "CardButton",
  props: ["uri", "title"]
};
</script>
