# Kokoa Clone 2020 Update

- 주석처리:  <!-- --> :ctrl+/

- 도큐먼트 단축키 : !

- 무료아이콘
  https://heroicons.dev/
  https://fontawesome.com/start (유료로 사용할거면 이메일주면됨,

  무료로할거면 밑에 코드 복붙해서 body 마지막!에 넣기-무료아이콘 찾아서 코드 복사해서 html에 붙여넣기)

  ```html
   <script
        src="https://kit.fontawesome.com/6478f529f2.js "
        crossorigin="anonymous"
      ></script>
  ```

  ```html
  <i class="fas fa-battery-full fa-lg"></i>
  ```

  fa-lg  : 폰 사이즈 크게 하기

- 폰트

  https://fonts.google.com/ 

(폰트 선택- @import로선택해서 복사- css상단에 붙여넣어 추가하기-font-family복사해서 body{ 여기에 붙여넣기;} )

https://abcdqbbq.tistory.com/9 :reset css이다 브라우저의 스타일을 없앰

- 깃허브에 업로드 하기싫은 파일은 따로 빼는 방법

( VSC비주얼에서 .gitignore 라는 파일 만들기(무시하고 싶은 파일 이름을 기록하는 파일임)-

코드에 무시하고싶은 파일이름 적기(폴더면 /붙이고 적기) )

## index

1. BEM(Block Element Modifier)규칙

```html
 <body>
    <div class="status-bar">
      <div class="status-bar__column"></div>
    </div>
  </body>
```

- class="status-bar__column"인 이유: class="status-bar"안에  column이라는 뜻으로써

​	쉽게 알수있게 하기위해 작성했음, 

- css작성할때 id인가 class 인가 헷갈리기 때문에 위에 방법으로 보통 html은 class로 모두 작성함

2. 버튼 코드작성하는 방법 2가지

```html
<body>
<input type="submit">
<button></button>
</body>
```

3. css를 html에 링크거는 방법  

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="stylesheet" href="css/styles.css"/>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Welcome to Kokoa Clone</title>
  </head>
```

- <link rel="stylesheet" href="css/styles.css"/>

css폴더안에 있는 styles.css 파일을 html코드안에 링크를 건다.

4. class = .(dot)

```html
<div class="status-bar">
.
.
.
.status-bar{        }
```

