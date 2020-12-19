<style>
body {
  font-family: '나눔고딕', NanumGothic, Dotum, '돋움', sans-serif;
}
body,
ul,
ol,
li,
div,
a {
  margin: 0;
  padding: 0;
}
ul,
ol {
  list-style: none;
}
a {
  color: inherit;
  text-decoration: none;
}

.wrap {
  max-width: 700px;
  min-width: 500px;
  margin: 5px;
}
.menu {
  display: table;
  table-layout: fixed;
  width: 100%;
}
.menu_item {
  display: table-cell;
}
.menu_link {
  display: block;
  height: 36px;
  border: 1px solid #ddd;
  font-size: 12px;
  line-height: 36px;
  color: #333;
  text-align: center;
}
.menu_item + .menu_item .menu_link {
  margin-left: -1px;
}
.menu_item:hover .menu_link {
  color: green;
  font-weight: bold;
}
.menu_item.active .menu_link {
  /* 포지션을 주는 이유는 두칸위css가 포지션을 먹으면서 margin주었던게 다시 살아남. */
  position: relative;
  border-color: #555;
  font-weight: bold;
  color: #fff;
  background-color: gray;
}
</style>

<template>
  <div class="wrap">
    <ul class="menu">
      <li class="menu_item"><a href="#" class="menu_link">메일</a></li>
      <li class="menu_item active"><a href="#" class="menu_link">카페</a></li>
      <li class="menu_item"><a href="#" class="menu_link">소프트웨어</a></li>
      <li class="menu_item"><a href="#" class="menu_link">지식백과</a></li>
      <li class="menu_item"><a href="#" class="menu_link">영화</a></li>
    </ul>
  </div>
</template>
