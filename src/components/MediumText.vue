<template>
  <p class="medium-text">
   <slot></slot>
  </p>
</template>

<script>
  export default {
    name: 'MediumText'
  }
</script>

<style scoped>
.medium-text {
    margin-top: 10px;
}
</style>
