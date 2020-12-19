<template>
  <div id="app">
    <Menu2 />
  </div>
</template>

<script>
import Menu2 from './components/menu/Menu2.vue';

export default {
  name: 'App',
  components: {
    Menu2,
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
