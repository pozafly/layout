<template>
  <div class="tab_wrap">
    <ul class="tab">
      <li class="tab_item active">
        <button type="button" name="button" class="tab_btn">인기순</button>
      </li>
      <li class="tab_item">
        <button type="button" name="button" class="tab_btn">조회순</button>
      </li>
      <li class="tab_item">
        <button type="button" name="button" class="tab_btn">날짜순</button>
      </li>
    </ul>
    <div class="tab_panel_wrap active">
      <h3>인기순 콘텐츠</h3>
      <ol class="tab_panel">
        <li class="panel_item">
          <a href="#" class="item_link">
            1. 서울-런던 30분 만에 도착.. 장거리 로켓 여행, 2030년 내 가능
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            2. 웬만해선 안 죽는다는 '물곰'에게서 극한생존 열쇠 찾는다
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            3. 애플, '에어팟 2세대' 발표
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            4. 한국어 지원하는 미승인 성인게임물 범람
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            5. [이슈+] '혁신없는 가격인상' ...에어팟2, 애플 충성고객마저 떠난다
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            6. KAIST, 세탁 가능한 입는 디스틀레이개발
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            7. "세계 최초 5G 상용화" ... 삼성 '갤럭시 S10 5G' 다음달 5일 출시
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            8. 중국업체, 국산 배터리 탑재 전기차 5대 형식승인 신청
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            9. 미 마이크론 '이례적' D램 낸드 감산 ... 메모리 업황 회복 기대
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            10. 아흔살 의사의 건강비결은 '매일 15분 맨손 운동'
          </a>
        </li>
      </ol>
    </div>
    <div class="tab_panel_wrap">
      <h3>조회순 콘텐츠</h3>
      <ol class="tab_panel">
        <li class="panel_item">
          <a href="#" class="item_link">
            1. 서울-런던 30분 만에 도착.. 장거리 로켓 여행, 2030년 내 가능
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            2. 웬만해선 안 죽는다는 '물곰'에게서 극한생존 열쇠 찾는다
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            3. 애플, '에어팟 2세대' 발표
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            4. 한국어 지원하는 미승인 성인게임물 범람
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            5. [이슈+] '혁신없는 가격인상' ...에어팟2, 애플 충성고객마저 떠난다
          </a>
        </li>
      </ol>
    </div>
    <div class="tab_panel_wrap">
      <h3>날짜순 콘텐츠</h3>
      <ol class="tab_panel">
        <li class="panel_item">
          <a href="#" class="item_link">
            1. 서울-런던 30분 만에 도착.. 장거리 로켓 여행, 2030년 내 가능
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            2. 웬만해선 안 죽는다는 '물곰'에게서 극한생존 열쇠 찾는다
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            3. 애플, '에어팟 2세대' 발표
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            4. 한국어 지원하는 미승인 성인게임물 범람
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            5. [이슈+] '혁신없는 가격인상' ...에어팟2, 애플 충성고객마저 떠난다
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            6. KAIST, 세탁 가능한 입는 디스틀레이개발
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            7. "세계 최초 5G 상용화" ... 삼성 '갤럭시 S10 5G' 다음달 5일 출시
          </a>
        </li>
        <li class="panel_item">
          <a href="#" class="item_link">
            8. 중국업체, 국산 배터리 탑재 전기차 5대 형식승인 신청
          </a>
        </li>
      </ol>
    </div>
  </div>
</template>

<style>
body {
  font-family: '나눔고딕', NanumGothic, Dotum, '돋움', sans-serif;
  font-size: 14px;
  line-height: 16px;
}
body,
ul,
ol,
li,
div,
a,
button {
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
.tab_wrap {
  width: 300px;
  margin: 20px auto 0;
}
.tab:after {
  content: '';
  clear: both;
  display: block;
}
.tab_item {
  float: left;
}
.tab_btn {
  width: 100px;
  height: 50px;
  font-size: 16px;
  color: #999;
  background-color: transparent;
  border: 1px solid #eee;
  outline: 0;
  cursor: pointer;
}
.tab_item + .tab_item .tab_btn {
  width: 101px;
  margin-left: -1px;
}
.tab_item .tab_btn:hover,
.tab_item.active .tab_btn {
  font-weight: bold;
  color: #000;
  border-bottom: 0;
}
.tab_panel_wrap {
  display: none;
}
.tab_panel_wrap.active {
  display: block;
}
.tab_panel_wrap {
  min-height: 350px;
  padding: 20px;
  border: 1px solid #eee;
  border-top: 0;
  box-sizing: border-box;
}
.tab_panel_wrap h3 {
  position: absolute;
  z-index: -1;
  color: transparent;
}
.panel_item .item_link {
  display: block;
  font-size: 14px;
  line-height: 30px;
  color: #333;
  /* 텍스트를 한줄로 만들기 위함. */
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  /* 여기까지 */
}
.panel_item:hover .item_link {
  font-weight: bold;
}
</style>
