<template>
  <div class="wrap">
    <div class="header">
      header
    </div>
    <div class="container">
      <div class="content">content</div>
    </div>
    <div class="footer">footer</div>
  </div>
</template>

<style>
html,
body,
.wrap {
  height: 100%;
}
.wrap {
  min-width: 800px;
  text-align: center;
}
.header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  height: 100px;
  background: lightgreen;
}
.container {
  min-height: 100%;
  margin-top: -100px;
}
.content {
  max-width: 1200px;
  margin: 0 auto;
  height: 300px;
  background: lightsalmon;
  padding-top: 200px;
}
.footer {
  height: 100px;
  background: lightblue;
}
</style>
