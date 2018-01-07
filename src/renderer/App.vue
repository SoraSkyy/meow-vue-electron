<template>
  <div id="app">
    <top-container></top-container>
  </div>
</template>

<script>
  import TopContainer from '@/components/TopContainer';

  export default {
    name: 'meow-vue-electron',
    components: {
      TopContainer,
    },
  };
</script>

<style>
  body {
    margin: 0px;
  }
</style>
