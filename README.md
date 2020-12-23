# sass practice

- Learn Sass In 20 Minutes | Sass Crash Course ; https://www.youtube.com/watch?v=Zz6eOVaaelI 따라하기

## setup

### Live Sass Compiler

- https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass
- vscode 확장도구 설치
- .scss 파일 저장시마다 normal css file로 변환해줌

## sass

```scss
// 변수
$primaryBtn: rgb(78, 201, 253);
$textColor: rgb(0, 0, 0);

button {
  background: $primaryBtn;

  // 중첩 nesting 가능
  //   & ; 상위 선택자
  &::after {
    content: "hellooo";
  }

  // 중첩된 속성
  margin: {
    top: 10px;
    left: 20px;
  }
  padding: {
    bottom: 40px;
    right: 30px;
  }
}
```
