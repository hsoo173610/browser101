project01 - Window-size 표기

목표 : 윈도우의 사이즈가 변동일 일어날때마다 업데이트하는것을 표기하는것이 프로젝트의 목표

설명 : 
1. window에게 addEventListener를 등록하게 되면 resize 될 때마다 콜백함수가 호출됨
2. window screen, outer, inner 와 documentElement.clientWidth 의 사이즈 업데이트
3. 위의 값들을 tag안에서 업데이트*
처음에 페이지가 로딩되게 하기 위해서 function updateTag 사용
