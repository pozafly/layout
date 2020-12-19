<template>
  <div class="wrap">
    <div class="header">
      header
    </div>
    <div class="content">content</div>
    <div class="footer">footer</div>
  </div>
</template>

<style>
.wrap {
  min-width: 800px;
  text-align: center;
}
.header {
  height: 100px;
  background: lightgreen;
}
.content {
  max-width: 1200px;
  /* 블럭요소를 가운데 정렬할 수 있는 margin 0 auto */
  margin: 0 auto;
  height: 300px;
  background: lightsalmon;
}
.footer {
  height: 100px;
  background: lightblue;
}
</style>
