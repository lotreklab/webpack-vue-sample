<template>
  <div class="full-width center-content">
    {{ msg }}
  </div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Hello world!'
      }
    }
  }
</script>

<style scoped>
  .full-width {
    width: 100%;
  }
  .center-content {
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
