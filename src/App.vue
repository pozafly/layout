<template>
  <div id="app">
    <Imglist1 />
  </div>
</template>

<script>
import Imglist1 from './components/imglist/Imglist1.vue';

export default {
  name: 'App',
  components: {
    Imglist1,
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
