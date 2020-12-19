<template>
  <div class="wrap">
    <div class="header">header</div>
    <div class="container">
      <div class="content">content</div>
      <div class="aside">aside</div>
    </div>
    <div class="footer">footer</div>
  </div>
</template>

<style>
/* * {
  border: 1px solid black;
} */
html,
body {
  margin: 0;
  padding: 0;
}
html,
body,
.wrap {
  height: 100%;
}
.header {
  height: 100px;
  background: lightgreen;
}
.container {
  position: relative;
  width: 800px;
  min-height: 100%;
  margin: -100px auto;
  padding: 100px 0;
  box-sizing: border-box;
}
.container:after {
  display: block;
  clear: both;
  content: '';
}
.content {
  float: left;
  width: 500px;
  height: 300px;
  background: lightsalmon;
}
.aside {
  float: left;
  width: 300px;
  height: 300px;
  background: lightseagreen;
}
.aside:after {
  position: absolute;
  top: 100px;
  bottom: 100px;
  right: 300px;
  content: '';
  width: 5px;
  background: #000;
}
.footer {
  height: 100px;
  background: lightblue;
}
</style>
