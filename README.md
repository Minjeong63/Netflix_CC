# 넷플릭스 클론코딩

1. 레이아웃 설계

2. 필요한 이미지, 로고 수집

3. 주어진 사진에 맞게 CSS 작성(외부 스타일 시트로 작성)

- general.css : body, p 태그에 전체적으로 적용할 스타일
- header.css : 넷플릭스 로고와 사용자 로고, 로고들을 합친 레이아웃에 해당하는 스타일
- main.css : 나머지 전체 스타일

4. 포인트

- Play, My list 버튼이 호버되었을 때 background 색 변경
- 영화 이미지가 호버되었을 때 이미지 사이즈 1.2배 커짐
- 메인 이미지와 영화 이미지 사이에 흐릿한 그라데이션
- 반응형(grid)으로 구현하여 특정 화면 크기일 떄 한 줄마다 나열되는 영화의 개수가 달라짐

5. 에러 사항

- 메인 이미지를 나타내는 div에 z-index: -1 값을 줬더니 그 위에 그려지던 버튼 hover가 먹히지 않음
  => z-index: -1 없애기

6. 아쉬운 점

- 스크롤이 생겨서 헤더가 고정된 채로 내려갈 때 헤더 배경색을 검정색으로 하고 싶었는데 css로 하지 못했음
