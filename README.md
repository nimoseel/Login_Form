# Login_Form

## 0412 login Form 구현 tip
- 가상요소 `::after`를 사용하여 clear-fix를 맨 마지막에 두어
앞에 있는 형제들의 float를 해제한다 

- 가상요소는 기본적으로 inline 요소로 width, height 쓸 수 없음 
- 가상요소에 float 사용하면 inline-block처럼 바뀌면서 width, height 값 적용

## 혼자하기 어려웠던 부분
- 가상요소를 사용하여 구분선 넣기, clear-fix 넣기
- float : left, right 주는 것 헷갈림 
