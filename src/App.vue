<template>
  <div id="app">
    <Menu1 />
  </div>
</template>

<script>
import Menu1 from './components/menu/Menu1.vue';

export default {
  name: 'App',
  components: {
    Menu1,
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
