<template>
  <div class="wrap">
    <div class="header">header</div>
    <div class="container">
      <div class="content">
        <div class="box">box</div>
      </div>
      <div class="aside">aside</div>
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
.header {
  height: 100px;
  background: lightgreen;
}
.container {
  display: table;
  min-height: 100%;
  table-layout: fixed;
  width: 800px;
  margin: -100px auto;
  padding: 100px 0;
  box-sizing: border-box;
}
.content {
  display: table-cell;
  width: 500px;
  background: lightsalmon;
  border-right: 5px solid black;
}
.aside {
  display: table-cell;
  width: 300px;
  background: lightseagreen;
}
.footer {
  height: 100px;
  background: lightblue;
}
.box {
  width: 300px;
  /* 이제 height 값을 container를 넘어서도 화면이 깨지지 않는다. */
  height: 300px;
  background: red;
}
</style>
