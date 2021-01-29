# Kakao-Clone v2
- 노마드코더 강의(Kakao-Clone v2)수강, 클론코딩으로 카카오톡 페이지를 만들며 HTML,CSS 학습

## HTML

### HTML이란?
- HyperText Markup Language의 약자
- HTML문서라고 불리며, HTML 태그(<태그이름>)들로 구성
- 태그는 웹 페이지나 디자인, 기능을 결정하는데 사용

### 기본 문법
- br : 줄 바꾸기
- p : 단락 바꾸기
- hr : 가로줄
- center ... /center : 가운데 정렬
- font ... /font : 폰트 변경
- ul li ... li .../ul : 순서없는 목록(동그라미)
- ol li ... li ... /ol : 순서있는 목록(숫자)
- table ... /table : 표 만들기
- tr ... /tr : 행
- td ... /td : 열

### 하이퍼텍스트(링크)
- a ... /a 형식으로 사용
- href : hypertext reference의 약자, 연결할 주소(절대주소 or상대주소)를 지정
- taget : 지정된 href 주소를 보여줄 때 설정
    * _self : 현재 브라우저에서 링크 연결
    * _blank : 새 창에서 링크 연결
    * _top : 현재 브라우저의 가장 위쪽으로 스크롤
- title : 마우스를 링크위에 올려두면 나오는 설명
- id : href 속성으로 링크가 아닌 현재 페이지에서 이동할 때 사용
- class : 요소에 스타일 시트를 적용하기 위한 구분자


## CSS

### CSS란?
- Cascading Style Sheets의 약자
- 마크업 언어가 웹사이트의 몸체를 담당 한다면 css는 옷과 악세사리처럼 꾸미는 역할을 담당
- 레이아웃과 스타일을 정의할 때의 자유도가 높다

### css 문법
- style.css 파일을 만들어 HTML파일에 link를 포함, 세부 css파일들을 import해줌(font는 google의 googlefont 이용하여 원하는 글씨체 import)
- solid class name을 사용하면 class의 재사용이 쉬워짐
- class에 스타일을 줄때 여러 클래스를 ,로 구분하여 한번에 사용 가능
- dispaly-flex : 수직으로 되어있는 요소들을 수평으로 적용 
- justify-content : 기본(중심) 축에서 요소 정렬
- align-items : 교차 축에서 요소 정렬
- opacity : 요소를 투명하게 만드는 속성
- box-sizing - border-box : 기존 box에서 패딩값을 추가하면 width+padding 값으로 box가 커지게 되어 기존 요소들이 밀리면서 화면 밖으로 밀려나는 경우 발생 -> padding값이 추가 되어도 box의 크기는 커지지 않고 자동으로 비율이 조정 되도록 함
- position : 태그들의 위치를 결정, 처음에는 static상태, 태그의 위치를 변경하고 싶으면 relative, absolute는 조상 element에 대해 상대적으로 배치, fiexd는 스크롤을 하여도 고정(반드시 width값을 설정)
- flex-direction : 플렉스 컨테이너 내의 아이템을 배치할 때 사용할 주축 및 방향을 지정
- icon의 div는 input 다음에 해야 함 
