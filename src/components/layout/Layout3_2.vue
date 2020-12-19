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
body {
  height: 100%;
}
.wrap {
  height: 100%;
  min-width: 800px;
  text-align: center;
}
.header {
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  height: 100px;
  background: lightgreen;
}
.container {
  min-height: 100%;
  padding: 100px 0;
  box-sizing: border-box;
}
.content {
  max-width: 1200px;
  margin: 0 auto;
  height: 2300px;
  background: lightsalmon;
}
.footer {
  position: fixed;
  bottom: 0;
  right: 0;
  left: 0;
  height: 100px;
  background: lightblue;
}
</style>
