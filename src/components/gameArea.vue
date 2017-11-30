<template lang="html">
  <div class="game-area">
    <slot></slot>
    <slot name="sidebar"></slot>
  </div>
</template>

<script>
export default {
  name: "game-area"
}
</script>

<style lang="css">
</style>
