margin
======
> **margin**은 지정한 요소와 다른 요소 간의 여백 간격을 정하는 CSS의 속성이다. 간격은 px(픽셀) 단위로 정하며, 하나만 입력 시 4방향의 간격, 2개 입력 시 순서대로 위,아래 / 좌우 간격, 3개 전부 입력 시 위, 오른쪽, 아래, 왼쪽 간격을 정한다.

padding
=======

> **margin**이 있고, 그 안에 **border**(말 그대로 경계이다)가 있으며, **border**와 내용의 간격이 **padding**이다. 여백 간격을 정하는 방법은 **margin**과 동일하다.

둘을 합쳐서 실전에서 사용해보자.

```css
.heads{
    margin: 10px;
    border: 1px solid black;
    padding: 10px;
    color: blue;
    background-color:bisque;
}
```

현재 내 사이트에 사용중인 코드를 그대로 가져왔다. 한 줄씩 보자.
1. margin을 전 방향 10px로 설정(다른 요소와의 간격)
2. border의 두께를 1px, 색을 solid black으로 지정
3. padding을 전 방향 10px로 설정(border와 내용 사이의 간격)

이런 식으로 활용하면 된다!

[내 홈페이지 링크](https://immortalchar-devintroclass.vercel.app/)