project01 - Window-size 표기
설명 : 
window에게 addEventListener를 등록하게 되면 resize 될 때마다 콜백함수가 호출됨
window screen, outer, inner 와 documentElement.clientWidth 의 사이즈 업데이트
위의 값들을 tag안에서 업데이트*
처음에 페이지가 로딩되게 하기 위해서 function updateTag 사용


project02, 03 - 좌표, 윈도우 스크롤링 apis
설명 : 
스페셜 div를 클릭했을때 client x,y와 page x,y 출력
클릭했을때 domrect 정보 받아옴
element.getboundingclientrect();
scollby, scollto, scollinto


project04 - 좌표 007
설명 : 
브라우저 창에서 마우스를 움직이면 마우스를 따라다니는 좌표가 출력


project05 - find a rabbit (scroll 적용)
설명 : 
const button = document.querySelector('button'); - 버튼 값 불러오기
const rabbit = document.querySelector('#rabbit'); rabbit id 값 불러오기 
button.addEventListener('click', () => { - 버튼을 클릭하면
rabbit.scrollIntoView({ behavior: 'smooth', block: 'center' }); rabbit 으로 scrollIntoView 하는데, 
begavior은 smooth, block은 center로 적용

