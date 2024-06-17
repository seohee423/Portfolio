# 포트폴리오 작업 일지 (240527 - )
https://seohee423.github.io/portfolio/

----

## 240617
#### 디자인
- 릴리바이레드 프로젝트 상세페이지 디자인 시안 작업<br>
- 릴리바이레드 프로젝트 상세페이지 내용 작성
#### html
- 릴리바이레드 상세페이지 html 마크업 작업
#### css
- 릴리바이레드 상세페이지 css 스타일 작업<br>

## 240615
#### html
- 경기도박물관 상세페이지 html 마크업 작업
#### css
- 경기도박물관 상세페이지 css 스타일 작업<br>
#### js
- 상세페이지 header 색상 변경 스크롤 이벤트 구현

## 240614
#### 디자인
- 경기도박물관 프로젝트 상세페이지 내용 작성<br>
- 경기도박물관 프로젝트 상세페이지 디자인 시안 작업 완료

## 240613
#### html&css
- project 영역에 개인 작업 '경기도박물관' 추가
#### 디자인
- 경기도박물관 프로젝트 상세페이지 디자인 시안 작업<br>
- 경기도박물관 프로젝트 상세페이지 내용 작성

## 240605  
#### html
- a태그에 필요한 링크 연결<br>
- 마우스 커서 이미지 첨부
#### js
- 페이지 전체 배경색이 동일해 각 영역을 구분하기 어렵고, 가독성이 떨어짐<br>
  → 스크롤 움직임에 따라 영역을 이동할 수 있는 스크롤 이벤트 적용<br>
  → 모든 영역의 높이값을 100vh로 동일하게 설정
  
## 240604  
#### html
- 파비콘 : ico 파일 형식만으로는 적용되지 않아 webmanifest파일 연결 후 적용<br>
- 오픈그라피 설정<br>
#### css
- 스크롤 바 너비, 색상 변경<br>
#### js
- main, contact 영역 배경 색상이 부드럽게 변하는 이벤트<br>
- 스크롤을 내리거나 올리면 배경 색상 변경 이벤트가 중지, 시작되도록 함<br>
  → window.scrollY로 스크롤 위치를 계산하여 main과 contact 영역을 벗어나면 색상 변경이 중지되도록 설정

## 240603  
#### 디자인
- main 마우스 이미지 누끼 작업<br>
#### js
- main 영역에서 마우스를 움직이면 이미지가 무작위로 나오는 이벤트를 구현하기 위해 랜덤함수 Math.random() 사용<br>
- display: none;으로 마우스를 움직이지 않을 때에는 이미지가 숨겨지도록 설정함

## 240602  
#### js
- 전체 영역 타이틀의 알파벳이 바뀌는 슬라이드 쇼 이벤트 적용<br>
- 타이틀 알파벳 일러스트의 사이즈가 각기 달라 부자연스럽게 적용됨<br>
  → 일러스트의 높이값을 동일하게 맞추고 position으로 재정렬하여 해결

## 240601  
#### js
##### &lt;project 영역 슬라이드 박스 작업&gt;<br>
- 우측 슬라이드를 클릭했을 때 너무 많이 이동해 슬라이드 좌측이 잘려 보이는 문제<br>
  → 슬라이드 전체 너비 지정, 우측 슬라이드를 클릭했을 때 슬라이드 전체가 X축 기준 좌측으로 이동하도록 translateX에 % 단위로 값을 설정함<br>
- 스크립트가 슬라이드 4개에 동일하게 적용되지 않는 문제 발생<br>
  → 각 슬라이드의 클래스명을 변경하여 각 슬라이드별로 다른 스크립트 작성

## 240531
#### js
##### &lt;project 영역 슬라이드 박스 작업&gt;<br>
- 슬라이드 버튼 사이즈가 작아 사용자가 인식하기 어려움<br>
  → 버튼 없이 박스 자체를 클릭해서 슬라이드할 수 있도록 디자인 변경<br>
- 좌측 이미지 박스가 중앙 정렬되지 않는 문제<br>
  → 슬라이드 전체를 감싸고 있는 .project-contents의 초기 위치를 translateX로 조정함<br>
- 스크롤을 내리면 우측 소개글 박스가 뷰포트 안으로 진입하도록 스크립트 작성

## 240530
#### js
- about 영역 소개글이 아래에서 위로 올라오는 이벤트 적용<br>
- footer contact 아이콘에 @keyframe으로 회전하는 애니메이션 적용<br>

## 240529 
#### css
- 각 페이지별 적용할 이벤트 정리<br>
- 마우스 hover 이벤트 적용<br>
(header 메뉴, about 키워드 박스, project 더보기 버튼, skills&tools 텍스트 박스, contact 이메일/링크)<br>
- about 페이지 소개글 드래그 시 색상 변경 : ::selection으로 설정

## 240528
#### css
- css 스타일 작업<br>
- skills&tools 영역 : 박스 안의 텍스트와 아이콘을 일정하게 정렬하기 위해 grid, display 사용<br>
  → 다양한 모니터 사이즈에서도 무너져 보이지 않도록 grid의 높이값을 %로 설정 <br>

## 240527
#### 디자인
- 디자인 시안 작업 완료
#### html
- 디렉토리 구성<br>
- html 마크업 작업

## 240526
#### 디자인
- 페이지별 타이틀 이벤트에 사용할 알파벳 일러스트 제작<br>
- 프로젝트 목업 제작

## 240525
#### 디자인
- 메인 페이지 디자인 시안 작업

## 240524
#### 디자인
- 메인 페이지 레이아웃 구성