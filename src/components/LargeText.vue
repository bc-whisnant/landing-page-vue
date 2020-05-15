<template>
  <p class="large-text">
   <slot></slot>
  </p>
</template>

<script>
  export default {
    name: 'LargeText'
  }
</script>

<style scoped>
.large-text {
    font-size: 25px;
    line-height: 1.5em;
}
</style>
