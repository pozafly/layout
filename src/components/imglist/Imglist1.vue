<template>
  <div class="wrap">
    <div class="main_wrap">
      <h1>TOP100</h1>

      <div class="content">
        <p class="noti_txt">
          8.21 오전 9시 ~ 오전 10시 기준 (재생수, 재생시간, 좋아요)
        </p>
        <ol class="main_list">
          <li>
            <a href="#" class="item_link">
              <div class="img_box">
                <img src="../../assets/a.png" alt="" />
              </div>
              <div class="info">
                <span class="category">산악스키</span>
                <p class="title">오스트리아 최대의 산악스키 연맹,</p>
              </div>
            </a>
          </li>
          <li>
            <a href="#" class="item_link">
              <div class="img_box">
                <img src="../../assets/a.png" alt="" />
              </div>
              <div class="info">
                <span class="category">산악스키</span>
                <p class="title">오스트리아 최대의 산악스키 연맹,</p>
              </div>
            </a>
          </li>
          <li>
            <a href="#" class="item_link">
              <div class="img_box">
                <img src="../../assets/a.png" alt="" />
              </div>
              <div class="info">
                <span class="category">산악스키</span>
                <p class="title">오스트리아 최대의 산악스키 연맹,</p>
              </div>
            </a>
          </li>
        </ol>
      </div>
    </div>

    <div class="sub_list">
      <ol class="sub_list">
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
        <li>48x48</li>
      </ol>
    </div>
  </div>
</template>

<style>
html,
body,
.wrap {
  margin: 0;
  padding: 0;
}
body {
  font-family: '돋움', dotum, Helvetica, sans-serif;
  font-size: 15px;
  line-height: 18px;
  color: #3c3c3c;
}
a {
  color: inherit;
  text-decoration: none;
  vertical-align: top;
}
h1 {
  width: 1000px;
  margin: 0 auto;
  padding: 20px 0;
  font-size: 26px;
  line-height: 38px;
  color: #000;
}
img {
  vertical-align: top;
}
ol {
  list-style: none;
  font-size: 14px;
  line-height: 14px;
  text-align: center;
}
.main_wrap {
  background-color: #ececec;
}
.main_wrap .content {
  position: relative;
  width: 1000px;
  margin: 0 auto;
  padding: 50px 0 20px;
}
.main_wrap .noti_txt {
  position: absolute;
  top: 20px;
  right: 0;
  font-size: 12px;
  color: #7c7c7c;
}
.main_list li {
  float: left;
}
.main_list:after {
  content: '';
  display: block;
  clear: both;
}
.main_list li + li {
  margin-left: 17px;
}
.main_list .item_link {
  position: relative;
  display: block;
}
.main_list .img_box img {
  width: 302px;
  height: 215px;
}
.main_list .img_box {
  position: relative;
}
.main_list .img_box:after {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
  content: '';
  background-color: rgba(0, 0, 0, 0.2);
  border: 1px solid rgba(0, 0, 0, 0.05);
}
.main_list .info {
  position: absolute;
  right: 15px;
  bottom: 8px;
  left: 15px;
  color: #fff;
  overflow: hidden;
}
.main_list .cartegory {
  font-size: 14px;
  line-height: 18px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
.main_list .title {
  margin-top: 3px;
  font-size: 14px;
  line-height: 22px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
</style>
