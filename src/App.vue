<template>
  <div id="app">
    <Tap1 />
  </div>
</template>

<script>
import Tap1 from './components/tap/Tap1.vue';

export default {
  name: 'App',
  components: {
    Tap1,
  },
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
}
#app {
  height: 100%;
}
</style>
