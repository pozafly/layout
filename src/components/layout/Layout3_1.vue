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
  left: 0;
  right: 0;
  height: 100px;
  background: lightgreen;
}
.container {
  min-height: 100%;
  margin-top: -100px;
  padding-top: 200px;
  box-sizing: border-box;
}
.content {
  max-width: 1200px;
  margin: 0 auto;
  height: 300px;
  background: lightsalmon;
}
.footer {
  height: 100px;
  background: lightblue;
}
</style>
