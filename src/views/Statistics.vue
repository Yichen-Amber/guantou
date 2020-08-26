<template>
  <Layout class="nav-wrapper">
    statistics.vue

  </Layout>
</template>

<script lang="ts">

  export default {
    name: 'Statistics'
  };
</script>

<style scoped lang="scss">
  .nav-wrapper {
    border: 1px solid green;
    display: flex;
    flex-direction: column;
    height: 100vh;
  }

  .content {
    border: 1px solid blue;
    overflow: auto;
    flex-grow: 1;
  }
</style>