<template>
  <div class="container">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Container'
}
</script>

<style scoped>
.container {
  max-width: 50%;
  margin-left: auto;
  margin-right: auto;
}
</style>
