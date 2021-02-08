# kokoa-clone-2021
메신저 어플을 따라해보자. by SaintKim

# 챌린지 1회차 코딩 결과물

<img src = "/img/challengeday_1.png" width="40%" height="20%" >  

시멘틱, form,input tag의 사용

html 태그, 속성 등을 알고 싶을 때,

> https://developer.mozilla.org/ko/docs/Web/HTML

# 챌린지 2회차 코딩 결과물 



다른 요소가 옆에 올 수있는 것을 `inline`
> span, a , img

다른 요소가 옆에 올수없다면 `block` 

---

`box`가 가지는 요소
  - margin
    border의 바깥 공간 
 ```html
 margin: 20px;                --1
 margin: 20px 10px;           --2
 margin: 10px 20px 30px 40px; --3
 ```
 1. **모든 방향**(상,하,좌,우)에 20px씩 적용.
 2.  **상하,좌우** 에 20px, 10px씩 적용.
 3.  **시계방향**(상,우,하,좌) 순으로 10px,20px,30px,40px씩 적용.
<h3>collapsing margin</h3>
상,하에서만 발생하며, 서로 다른 박스의 경계가 같을 때 하나로 합쳐지는 현상

  - border
경계
  - padding
border로 부터 안쪽에 있는 공간  