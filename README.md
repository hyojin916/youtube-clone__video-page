#Youtube 영상 페이지 클론입니다.

1 commit
- Mobile-first로 만들기 위헤 모바일 크기일 때를 기준으로 페이지를 만들기 시작.
- position: fixed를 사용하여 header와 video 부분이 고정되면서 아래 리스트들이 움직이도록 하였습니다. 

2 commit
- html tag들과 구조를 더 보기 좋게 바꾸고 부족한 기능들을 추가하였습니다.
- div --> ul>li
- icon --> button > icon 
- media query 추가 
- class name 수정
- "video" tag 삽입 

3 commit (css)
- 주로 CSS 수정.
-  *(전체) 셋팅
``` 
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
``` 
- variable을 color, size, font size로 나누고 추가해서 더 쉽게 적용할 수 있도록 하였습니다.