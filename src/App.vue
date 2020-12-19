<template>
  <div id="app">
    <Layout3 />
  </div>
</template>

<script>
import Layout3 from './components/layout/Layout3.vue';

export default {
  name: 'App',
  components: {
    Layout3,
  },
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
}
#app {
  height: 100%;
}
</style>
