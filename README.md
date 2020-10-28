# Shopping Application으로 DOM 다루기

---

### 쇼핑 목록앱 만들기

---

- 1. HTML 마크업하기
  - 소제목(하얀원) -내용나열
  - 소제목(하얀원) -내용나열
    - 부과 설명
    - 부과 설명
- 2. CSS 스타일링(+ 유용한 사이트 몇가지)

  - 소제목(하얀원) -내용나열

- 3. Javascript 동적으로 만들기

  - 구현으로 들어가기 전에 정확하게 **어떻게 구현할 것인지 계획을 세우는것이 중요**하다.
    - 1. 사용자가 입력한 텍스트를 받아온다.
    - 2. 새로운 아이템을 만든다. (텍스트 + 삭제버튼)
    - 3. item 컨테이너 안에 새로 만든 아이템을 추가한다.
    - 4. input을 초기화 한다.

- 4. 디버깅하는 방법 (+ 주석 작성 시 유의사항)
  - 소제목(하얀원) -내용나열

---

---

[cssgradient](https://cssgradient.io/ "cssgradient")
[box-shadow](https://www.cssmatic.com/box-shadow "box-shadow")
[color-wheel](https://color.adobe.com/ko/create/color-wheel "color-wheel")

---

### 2.2 리액트 컨셉과 구현 사항

-
-
-
- ![RenderTree](/imgs/rendering.png)
- 구현으로 들어가기 전에 정확하게 **어떻게 구현할 것인지 계획을 세우는것이 중요**하다.
  :sparkles: 이번 챕터의 핵심 :sparkles:

>

```html

```

```javascript
const items = document.querySelector(".itmes");
const input = documnet.querySelector(".footer__input");
const addBtn = cocument.querySelector(".footer__button");

function onAdd() {
  // 1. 사용자가 입력한 텍스트를 받아온다.
  const text = input.value; //text는 위 DOM에 있는 input에 value를 통해 받아 올 수 있다.
  // console.log(text);
  // 2. 새로운 아이템을 만든다. (텍스트 + 삭제버튼)
  // 3. item 컨테이너 안에 새로 만든 아이템을 추가한다.
  // 4. input을 초기화 한다.
}

addBtn.addEventListener('click', () = >{
  onAdd();
});
```

```javascript
function test() {
  console.log("hello world!");
}
```

```javascript
function test() {
  console.log("hello world!");
}
```

[cssgradient](https://cssgradient.io/ "cssgradient")
[box-shadow](https://www.cssmatic.com/box-shadow "box-shadow")
[color-wheel](https://color.adobe.com/ko/create/color-wheel "color-wheel")
