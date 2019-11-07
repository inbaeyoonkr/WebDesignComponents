# 기억할 것들 정리

- inline : <a>, <span>, <strong>, <em>

* width, height 지정불가, 무조건 컨텐츠 크기 만큼으로 자동저절
* padding, margin은 좌우만 적용가능
* padding의 상하단은 시각적인 부분만 적용됨 (공간차지하지않음)

- block : <div>, <h1>, <p>, <ul>, <li>

* width, height, padding, margin 모두 적용 가능

- inline-block : <img>

* inline과 block의 장점들을 고루 가지고 있음
* width, height 지정 가능, 부모에게 text-align 적용 가능, 언제나 컨텐츠 크기만큼 조절됨
* margin, padding은 block과 같이 동작함

- display: 속성을 이용하면 상황에 따라 적절한 display 속성으로 변경 가능

* 주로 inline태그은 a태그를 block 으로 바꿀 때 사용한다.
  a {
  width: 200px;
  display: block;
  }

- 가운데 정렬하는 방법

* width를 준 다음 margin-left: auto; margin-right: auto; 를 줌
* margin: 0 auto; 와 똑같음
