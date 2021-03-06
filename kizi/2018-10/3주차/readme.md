# Tag Document

|태그|설명|
|:--------|:--------|
|`<br>`|줄바꿈 기능이 있는 홑태그 (line break)|
|`<p>`|문단을 나누고 한줄의 여백을 띄어줌, text-align 으로 문단정렬을 처리 (paragraph)|
|`<pre> `|문서 내용에 편집되어있는 모든 여백, 탭, 줄바꿈 등을 모양 그대로 화면에 보여줌|
|`<span> `|문장 내에서 일정 부분에 색상 변경등의 스타일을 지정하는 인라인 태그 (span - 범위)|
|`<hr> `|주제번경, 내용구분등을 위해 수평선을 삽입 (horizontal rule)|
|`<div>`|높이와 너비를 가진 독립된 영역을 만들어 웹페이지 화면에 블록 구조로 표현. (division)|
|`<H1> ~ <H6> `|제목을 표시하는 태그, 숫자가 클수록 글자크기는 작다 (heading)|
|`<abbr>`|축약어를 표현함. *title 로 지정하면 마우스를 올리면 화면에 말풍선으로 나타남|
|`<meter> `|측정값을 그래픽(그래프)형태로 표현  사용예) `<meter value=”측정값” min=”최소값” max=”최대값”>`|
|`<time> `| 작성된 날짜를 사람뿐만 아니라 기계도 알아볼 수 있게 하는 시맨틱 태그. 사용예) `<time datetime=”날짜, 시간(2016-06-25T15:30:00)”> 내용 </time>`|
|`<address>`|주소나 연락처의 의미로 기울임|
|`<cite>`|책, 그림등의 제목을 알리는 의미로 기울임|
|`<em>`|강조의 의미로 기울임 (emphasis)|
|`<i> `|이탤릭체로 기울임 표현 (italic)|
|`<b> `|강조의 의미로 굵게 (bold)|
|`<strong>`| 강한 강조의 의미로 굵게|
|`<blockquote> `|긴글 인용문을 들여쓰기 처리 (quote - 인용하다|
|`<q>`|짧은 글 인용문을 “큰따옴표” 처리 (quote)|
|`<mark> `|하이라이트 마크 표현, 형광펜 처럼 (mark - 표시하다) [ex) 흐헑]|
|`<ruby> `|루비문자 선언 (동아시아 문자들에서, 글자위에 작게 발음 설명이 들어감)  -->|
|`<rt>`|루비문자의 설명(발음)표현|
|`<sub> `|아래 첨자 표현 (subscript) [ex) X2]|
|`<sup>`|위 첨자 표현 (superscript) [ex) H2O]|
|`<del>`|가운데 줄이 들어간 글자 표현 (delete) [ex) 으아ㅏ아아아]|
|`<ol> `|항목앞에 순서를 표현하여 목록을 만든다. (ordered list) <br> *type  : 1(숫자), a,A(알파벳 소, 대문자), i,l(로마자 소, 대문자)<br> *start : 시작 숫자를 지정<br> *reversed : 숫자를 역순으로 정렬|
|`<li>`|록에 항목을 추가 (list item)|
|`<ul>`|항목앞에 순서없이 목록을 만든다 (unordered list)<br>*type : square(네모), circle(동그라미)|
|`<li>`|목록에 항목을 추가|
|`<dl>`|정의 목록 (definition list)|
|`<dt>`|정의 항목 용어 (definition term)|
|`<dd> `|정의 항목 용어 설명 (definition description)|
|`<img>`|이미지파일을 삽입 (imagine dragons)<br>*src - 이미지의 경로 지정<br>*alt - 이미지가 보이지 않을때 출력할 대체 텍스트<br>*title - 마우스 올릴 시 보여줄 추가 설명<br>*width/height - 가로/세로길이 설정|
|`<a>`|다른 문서, URL연결 (anchor - 닻 (배에다는 그거))<br>*href - 연결할 문서의 경로 또는 URL지정<br>*target -  _blank  - 새로운창에서 열기<br>_self     - 현재 탭에서 열기<br>*title - 마우스 올릴시 추가 설명|
|`<a> `|문서 내에서 스크롤 이동할때, 클릭를 누르면 내용임으로 스크롤 이동 `<a href=”#id”>클릭</a>``<a id=”id”>내용임</a>`|
|`<table>`|표를 정의|
|`<tr>`|행을 구성 (table row)|
|`<td> `|열을 구성 (table data)|
|`<th>`|행,열의 머리말, 가운데 정렬및 굵은글씨 표현 (table head)|
|`<video>`|재생 안될시 대체 텍스트 (생략가능) <br>*src - 비디오파일 경로 설정<br>*autoplay - 자동 재생 기능<br>*controls - 컨트롤 바 표시<br>*poster - 동영상 재생이 안될 시 대체이미지<br>*width, height - 가로/세로 길이 지정|
|`<source> `|만약 브라우저에서 해당 확장자를 지원하지 않을 시 준비해 둔 다른 확장자의 동영상 실행<br>*src - 비디오파일 경로 설정<br>*type - 비디오 파일의 타입 지정 (video/egg , video/mp4 등...)|
|`<audio>`| 재생 안될시 대체 텍스트(생략가능)<br>*src - 오디오파일 경로 설정<br>*autoplay - 자동 재생 기능<br>*controls - 컨트롤 바 표시<br>*loop - 반복 재생 기능|
|`<source>`|만약 브라우저에서 해당 확장자를 지원하지 않을 시 준비해 둔 다른 확장자의 오디오 실행<br>*src - 오디오파일 경로 설정<br>*type - 오디오 파일의 타입 지정 (audio/ogg , audio/mp3 등...)|
|`<embed>`|비디오/오디오/플래시 파일 등 플러그인이 설치된 또는 필요한 멀티미디어 파일을 재생<br>*src - 파일 경로 설정<br>*type - 비디오 파일의 타입 지정<br>*width, height - 가로/세로 길이 지정|
|`<area>`||
|`<article>`|`<article>` 태그는 독립적 인 독립 컨텐츠를 지정합니다. 기사는 독자적으로 이해해야하며 나머지 사이트와 독립적으로 기사를 배포 할 수 있어야함<br>`<article>` 요소에 대한 잠재적 인 출처 :<br>포럼 게시물<br>블로그 게시물<br>뉴스 기사<br>논평<br>|
|`<aside>`|`<aside>` 태그는 배치 된 내용을 제외하고 일부 내용을 정의, aside는 섹션으로 사용하는게 일반적이며, body내의 섹션과 분리되어 includes 하게 사용할 수 있게 하는것이 핵심. 또한 aside를 때냈을떄 기존 레이아웃이 무너지지 않으면 쵝오!|
|`<base>`|`<base>` 태그는 문서의 모든 상대 URL에 대한 기본 URL / 대상을 설정, 문서에는 최대 하나의 `<base>` 요소가있을 수 있으며 `<head>` 요소 내에 있어야함|
|`<bdo>`|bdo는 Bi-Directional Override를 표현,`<bdo>` 태그는 현재 텍스트 방향을 덮어 쓰는 데 사용됨|
|`<caption>`|`<caption>` 태그는 테이블 캡션을 정의<br>`<caption>` 태그는 `<table>` 태그 바로 뒤에 삽입<br>표 당 하나의 캡션 만 지정할 수 있습니다.<br>`<figcation`이 없던 떄에는 `<caption>`태그를 대체해서 사용했었다고 전해짐>|
|`<code>`|<code> 태그는 구문 태그입니다. 그것은 컴퓨터 코드를 정의|
|`<col>`|`<col>` 태그는 `<colgroup>` 요소 내의 각 열에 대한 열 속성을 지정 .|
|`<colgroup>`|`<colgroup>` 태그는 `<caption>` 요소 다음에 `<thead>`, `<tbody>`, `<tfoot>` 및 `<tr>` 요소 앞에 `<table>` 요소의 하위 항목이어야함.|
|`<dfn>`|용어를 정의할떄 사용함. ex `<p><dfn>`HTML`</dfn>` is the standard markup language for creating web pages.`</p>`<br>`<dfn> 태그의 가장 가까운 부모는 <dfn> 내부 용어에 대한 정의` / 설명을 포함해야합니다.|
|`<fieldset>`|`<fieldset>` 태그는 양식의 관련 요소를 그룹화하는 데 사용함`<fieldset>` 태그는 관련 요소 주위에 상자를 그림, legend태그로 상자의 제목을 설정|
|`<figcaption>`|`figure태그로 마크업된 사진의 제목을 나타냄`|
|`<figure>`|`<figure>` 요소를 사용하여 문서의 사진을 마크 업함|
|`<footer>`|`<footer> 태그는 문서 또는 섹션의 바닥 글을 정의`|
|`<form>`|`<form> 태그는 사용자 입력을위한 HTML 양식을 만드는 데 사용`<br>Action <br>autocomplete<br>accept-charset<br>enctype<br>method<br>name<br>novalidate<br>target|
|`<header>`|`<header> 요소는 소개 내용 또는 탐색 링크 모음을위한 컨테이너를 나타냄 하나의 문서에 여러 개의 <header> 요소를 포함 할 수 있음`|
|`<ins>`|`<ins> 태그는 문서에 삽입 된 텍스트를 정의`|
|`<iframe>`||
|`<kbd>`|`<kbd> 태그는 구문 태그입니다. 키보드 입력을 정의 ctrl+1 이런것`|
|`<label>`|`<label> 태그는 <button>, <input>, <meter>, <output>, <progress>, <select> 또는 <textarea> 요소에 대한 레이블을 정의`<br>`<label> 태그의 for 속성은 관련 요소를 묶는 관련 요소의 id 속성과 동일해야함` <br>for<br>label|
|`<legend>`|`<legend> 태그는 <fieldset> 요소에 대한 캡션을 정의`|
|`<link>`|`<link> 태그는 문서와 외부 리소스 간의 링크를 정의`|
|`<main>`|`<main> 태그는 문서의 주요 내용을 지정,  문서에 하나 이상의 <main> 요소가 없어야함`|
|`<map>`|`<map> 태그는 클라이언트 측 이미지 맵을 정의하는 데 사용됩니다. 이미지 맵은 클릭 가능한 영역이있는 이미지, <map> 요소의 필수 name 속성은 <img>의 usemap 속성과 연관되어 있으며 이미지와 맵 사이에 관계를 만듬, <map> 요소 는 이미지 맵에서 클릭 가능한 영역을 정의 하는 여러 <area> 요소를 포함`|
|`<meta>`|`<meta> 태그는 HTML 문서에 대한 메타 데이터를 제공합니다. 메타 데이터는 페이지에 표시되지 않지만 구문 분석이 가능`|
|`<nav>`|`<nav> 태그는 일련의 탐색 링크를 정의`|
|`<noscript>`|`<noscript> 태그는 브라우저에서 스크립트를 비활성화했거나 스크립트를 지원하지 않는 브라우저를 가지고있는 사용자를위한 대체 컨텐츠를 정의`|
|`<object>`|`<object> 태그는 HTML 문서에 포함 된 객체를 정의합니다. 이 요소를 사용하여 오디오, 비디오, Java 애플릿, ActiveX, PDF 및 Flash와 같은 멀티미디어를 웹 페이지에 포함 할 수 있음, <object> 태그를 사용하여 다른 웹 페이지를 HTML 문서에 포함 할 수도 있음`|
|`<optgroup>`|`<optgroup>은 관련 옵션을 드롭 다운 목록에 그룹화하는 데 사용`|
|`<option>`|`<option> 태그는 선택 목록에서 옵션을 정의, <option> 요소는 <select> 또는 <datalist> 요소 안에 있음`|
|`<output>`|`<output> 태그는 계산 결과 (예 : 스크립트에 의해 수행 된 것)를 나타냄` [참고](https://www.w3schools.com/tags/tag_output.asp)|
|`<param>`|`<param> 태그는 <object> 요소로 삽입 된 플러그인의 매개 변수를 정의하는 데 사용`|
|`<picture>`|`<picture> 태그는 웹 개발자가 이미지 리소스를보다 유연하게 지정할 수있게함`<br>srcset<br>media<br>sizes<br>type|
|`<progress>`|`<progress> 태그는 작업 진행율을 나타냄`|
|`<q>`|`<q> 태그는 짧은 인용 부호를 정의`|
|`<rp>`|`<rp> 태그는 루비 텍스트를 괄호로 묶어주고 루비 주석을 지원하지 않는 브라우저에 표시되도록 사용될 수 있음. 사실 루비관련 태그는 왜쓰는지 잘모르겟음..`|
|`<rt>`|`<rt> 태그는 루비 주석의 문자 (동아시아 타이포그래피)에 대한 설명이나 발음을 정의`|
|`<ruby>`|`<ruby> 태그는 루비 주석을 지정`|
|`<s>`|`<s> 태그는 더 이상 정확하지 않거나 관련성이없는 텍스트를 지정 >> html5 에선 del을 씁니다!! 이제 s는 마크업용으로는 안써여!`|
|`<samp>`|`<samp> 태그는 구문 태그입니다. 컴퓨터 프로그램의 샘플 출력을 정의 >> code 나 pre로 쓰는거에여!! 마찬가지로 마크업으로는 이제 안써여!`|
|`<section>`|`<section> 태그는 문서의 장, 머리글, 바닥 글 또는 문서의 다른 섹션과 같은 문서의 섹션을 정의`|
|`<select>`|`<select> 요소는 드롭 다운 목록을 만드는 데 사용, <select> 요소 의 <option> 태그는 목록에서 사용 가능한 옵션을 정의`|
|`<small>`|`<small> 태그는 작은 텍스트 (및 기타 측면 설명)를 정의`|
|`<strong> `|`<strong> 태그는 구문 태그입니다. 중요한 텍스트를 정의`|
|`<template>`|`<template> 태그는 클라이언트에서 숨겨진 내용을 보유함,<template> 태그 안의 내용은 렌더링되지 않음`|
|`<textarea>`|`<textarea> 태그는 여러 줄 텍스트 입력 컨트롤을 정의,텍스트 영역은 무제한의 문자 수를 유지할 수 있으며 텍스트는 고정 너비 글꼴 (일반적으로 Courier)로 렌더링`|
|`<title>`|`<title> 태그는 모든 HTML 문서에서 필요하며 문서의 제목을 정의`|
|`<thead>`|`<thead> 요소에는 하나 이상의 <tr> 태그가 있어야함`|
|`<tfoot>`|`<tfoot> 요소는 <thead> 및 <tbody> 요소 와 함께 사용되어 테이블의 각 부분 (바닥 글, 머리글, 본문)을 지정`|
|`<u>`|`<u> 태그는 철자가 틀린 단어 또는 중국어의 고유 명사와 같이 일반 텍스트와 스타일이 다른 텍스트를 나타냄`|
|`<var>`|`<var> 태그는 구문 태그입니다. 그것은 변수를 정의`|
|`<wbr>`|단어가 너무 길거나 브라우저가 잘못된 위치에서 줄 바꿈을 두려워하는 경우 <wbr> 요소를 사용하여 단어 나누기 기회를 추가 할 수 있음. HTML의 br형|

# SCSS Document

## Scss Seletor

```
<h1>hello
  <span class="son">world</span>
</h1>

<style>
  h1{
    color:blue;
    .son{
      color:red;
    }
  }

</style>
```
기본적으로 css와 셀렉하는게 같으나, 위와 같이 중첩해서 css를 작성할 수 있다.

```
.entry-content {
  p { font-size: 9.814rem; }
}

// compiled to
.entry-content p {
  font-size: 9.814rem;
}
```
특정 선택자 내에는 속성 정의만 들어오는 것이 아니라, nested된 속성 정의 블럭이 들어올 수 있다.


```
.entry-content {
  p {
    font: {
      family: "Noto Serif CJK KR", serif;
      size: 9.814rem;
      weight: 400;
    }
  }
}
```
선택자가 네스팅되는 것과 유사하게, 특정한 family로 묶여있는 속성들도 네스팅이 가능하다. 예를 들어 font의 경우 font-family, font-size, font-weight 등이 주로 세트로 정의되는데, 다음과 같이 하나의 세트(?)인 속성들은 속성의 하위 사전 형태로 작성할 수 있다.




## 상위요소 참조
```
a {
  text-decoration: none
  &:hover { text-decroation: underline; }
}
```

&을 사용하면 현재 블럭이 적용되는 셀렉터를 참조한다. 정확하게는 참조가 아닌 치환이다.  특히 현재 속성을 설정중인 셀렉터에 의사셀렉터를 적용할 때 유용하다.

위 선언은 아래와 같이 컴파일 된다.

```
a { text-decoration: none; }
a:hover { text-decoratino: underline; }
```

## 또다른 &사용법
```
.widget {
   font-weight: 400;
   &-area { font-weight: 600; }
   &-top_posts { font-weight: 1000; }
}
```
이 & 은 현재 셀렉터로 치환되기 때문에 다음과 같이 복합어로 이루어진 클래스들을 하나의 블럭으로 네스팅하여 묶을 때도 유용하게 쓰일 수 있다. 워드 프레스 테마의 경우를 예로 들면, 위젯들은 모두 widget-**** 의 식으로 클래스 이름을 갖는다.  이 들을 개별 셀렉터로 쓰지 않고 아래처럼 네스팅할 수 있다는 이야기다.

위 예에서 & 은 .widget 으로 치환되므로 컴파일된 결과는 아래와 같다.

```
.widget { font-weight: 400; }
.widget-area { font-weight: 600; }
.widget-top_posts { font-weight: 1000; }
```

## 변수와 연산자
색상이나 선 스타일, 폰트 패밀리등은 대체로 사이트 내에서 공통적으로 정의해놓은 값을 쓰는 경우가 많다. 이들을 매번 지정하지 않고 변수로 들어서 사용하면 변경 시점에 변수의 내용만 수정하여 모든 곳의 값을 공통적으로 바꿀 수 있을 것이다.

| 타입      | 설명 |
|:--------|:--------|
|숫자값     |숫자 리터럴로 쓰인 값은 숫자로 판단한다. 크기를 나타내는 단위가 붙은 경우도 숫자로 취급한다. 12px, 1.534rem|
|문자열      |문자의 경우 기본적으로 따옴표 여부에 상관없이 문자열로 취급한다.
|색상값|색상명이나 색상리터럴로 표기된 값은 색으로 인식한다. (blue, #aa33cc, rgba(255, 0, 0, 0.3))|
|불리언|true, false|
|널|null|
|리스트|리스트 내 원소는 동일 타입일 필요는 없으며, 괄호 속에 컴마나 공백으로 구분된 값들을 리스트로 본다.|
|맵|괄호 속에서 : 으로 키 : 값을 구분하여 쓴다.|


## 문자열의 치환 및 내삽(interpolation)

#{...} 을 사용하면 문자열 내에 표현식의 결과를 내삽하거나, 다른 변수의 내용으로 치환하는 것이 가능하다. 이는 속성값의 일부 혹은 전체 뿐만 아니라 속성명이나 셀렉터에 대해서도 적용 가능하다.
```
$foo: bar;
$fontsize: 12px;
$lineheight: 30p;

p {
  font: #{$fontsize}/#{$lineheight};
  &.#{$foo} { color: red; }
}
```

이 예제는 다음과 같이 컴파일 된다.
```
p { font: 12px/30px; }
p.bar { color: red; }
```

#{}를 이용해서 코드의 어디든지 변수 값을 넣을 수 있습니다.
```
$family: unquote("Droid+Sans");
@import url("http://fonts.googleapis.com/css?family=#{$family}");
```
```
@import url("http://fonts.googleapis.com/css?family=Droid+Sans");
```
Sass의 내장 함수 unquote()는 문자에서 따옴표를 제거합니다.


## 변수 유효범위(Variable Scope)
변수는 사용 가능한 유효범위가 있습니다.
선언된 블록({}) 내에서만 유효범위를 가집니다.

변수 $color는 .box1의 블록 안에서 설정되었기 때문에, 블록 밖의 .box2에서는 사용할 수 없습니다.
```
.box1 {
  $color: #111;
  background: $color;
}
// Error
.box2 {
  background: $color;
}
```

## @at-root (중첩 벗어나기)
중첩에서 벗어나고 싶을 때 @at-root 키워드를 사용합니다.
중첩 안에서 생성하되 중첩 밖에서 사용해야 경우에 유용합니다.

SCSS:
```
.list {
  $w: 100px;
  $h: 50px;
  li {
    width: $w;
    height: $h;
  }
  @at-root .box {
    width: $w;
    height: $h;
  }
}
```
Compiled to:
```
.list li {
  width: 100px;
  height: 50px;
}
.box {
  width: 100px;
  height: 50px;
}
```

아래 예제 처럼 .list 안에 있는 특정 변수를 범위 밖에서 사용할 수 없기 때문에, 위 예제 처럼 @at-root 키워드를 사용해야 합니다.(변수는 아래에서 설명합니다)
```
.list {
  $w: 100px;
  $h: 50px;
  li {
    width: $w;
    height: $h;
  }
}

// Error
.box {
  width: $w;
  height: $h;
}
```
## 중첩된 속성
font-, margin- 등과 같이 동일한 네임 스페이스를 가지는 속성들을 다음과 같이 사용할 수 있습니다.

SCSS:
```
.box {
  font: {
    weight: bold;
    size: 10px;
    family: sans-serif;
  };
  margin: {
    top: 10px;
    left: 20px;
  };
  padding: {
    bottom: 40px;
    right: 30px;
  };
}
```
Compiled to:
```
.box {
  font-weight: bold;
  font-size: 10px;
  font-family: sans-serif;
  margin-top: 10px;
  margin-left: 20px;
  padding-bottom: 40px;
  padding-right: 30px;
}
```
## 임포트
@import 지시어를 이용해서 다른 css 파일을 임포트할 수 있다. 사실 이 기능은 css의 원래 기능이다. 대신 css 파일이 아닌 scss, sass 파일을 임포트할 수 있다.


## 확장
확장은 이미 정의해둔 다른 셀렉터의 속성에 현재 셀렉터가 얹어가는 효과를 낼 수 있다.  따라서 특정한 클래스군에 대해서 베이스 클래스에서 공통 속성을 지정하여, 다른 클래스들이 베이스 클래스를 상속받는 효과를 낼 수 있다.  확장 문법은 @extend 최상위셀렉터의 형태로 사용한다.
```
// 베이스 클래스
.message {
  border: 1px solid #ccc;
  padding: 10px;
  color: #333;
}

.success {
  @extend .message;
  border-color: green;
}

.error {
  @extend .message;
  border-color: red;
}
```
공통 속성은 각각의 셀렉터 내로 포함되는 것이 아니라, 상속받는 셀렉터가 상위 셀렉터로 선언 부가 병합된다.  따라서 위 예제는 아래와 같이 컴파일 된다.
```
.message, .success, .error {
  border: 1px solid #cccccc;
  padding: 10px;
  color: #333;
}

.message { border-color: green; }
.error { border-color: red; }
```
## 믹스인
공통적으로 많이 쓰이는 CSS 선언값들을 묶어서 믹스인으로 만들어 재사용이 가능하게끔 할 수 있다. 변수는 단일 값을 담을 수 있는 것에 비해, 믹스인은 여러 속성의 정의 및 셀렉터에 대한 속성 전체등 블럭 단위로 재사용할 수 있다.

특별히 믹스인을 정의할 때에는 파라미터를 받을 수 있게끔 할 수 있기 때문에 단순 복붙이 아닌 파라미터 값에 따른 가변적 속성 집합을 만들어 유용하게 쓸 수 있다.

다음 예는 둥근 외곽선을 지정할 때 벤더별로 다른 접두어가 붙는 속성들을 매번 반복해서 쓰지 않도록 하는 테크닉이다.
```
@mixin border-radius($radius) {
  -webkit-border-radius: $radius;
  -moz-border-radius: $radius;
  -ms-border-radius: $radius;
  border-radius: $radius;
}

.box { @include border-radius(10px); }
```
위 예에서 보듯 믹스인은 @mixin 키워드를 이용해서 이름과 인자를 선언한다. 인자가 필요없는 믹스인은 ($인자) 부분을 생략할 수 있다. 인자는 일반 변수처럼 정의한다.

믹스인을 사용할 때에는 @include 지시어를 사용한다.

## 믹스인의 인자값
믹스인의 인자는 선언하는 만큼 사용할 수 있다. 만약 인자값에 디폴트를 적용하고 싶다면, 변수 선언과 같은 문법으로 인자변수의 초기값을 설정해 줄 수 있다.
```
@mixin dashed-box($color, $width: 2px) { .. }
```
@include 구문에서 인자값은 선언된 순서대로 쓸 수 있으며, 보다 명확한 구분을 위해서 인자의 이름을 직접 기입할 수 있다. 인자의 각 이름을 명시한 경우에는 순서가 바뀌어도 상관없다.
```
.box { @incluxe dashed-box($width: 3px, $color: #eee) }
```
## 리스트 인자
인자명에 ... 을 붙이면 단일 값이 아닌 리스트로 인자를 받는 다는 의미이다. 이는 일련의 연속값을 속성으로 사용하는 경우에 활용할 수 있다.

이 문법은 파이썬의 *args, **kwds 등 시퀀스/맵 분해와 비슷하게 동작한다. 아래에서 살펴보겠지만 인자를 넣는 시점에도 같은 식으로 전달할 수 있다.

예를 들어 그림자 속성은 컴마로 구분된 리스트가 될 수 있다.
```
@mixin box-shadow($shadows...) {
  -moz-box-shadow: $shadows;
  -webkit-box-shadow: $shadows;
  box-shadow: $shadows;
}

.shadows { @include box-shadows(0px 4px 5px #666, 2px 6px 10px #999); }
```
... 표현은 리스트나, 맵을 개별 인자들로 분해해서 함수나 믹스인에 전달할 때 사용될 수 있다.
```
@mixin colors($text, $background, $border) {
  color: $text;
  background-color: $background;
  border-color: $border;
}

$values: #ff0000, #00ff00, #0000ff;
.primary { @include colors($values...); }
```
블럭을 믹스인에 넘기기
흔한 케이스는 아니지만, 블럭 자체를 믹스인에 넘겨줄 수 있다.  믹스인내에서 @content 지시어를 쓴 부분이 넘겨받은 블럭으로 치환된다.
```
@mixin code-inline {
  code {
    background-color: #cecece;
    padding: 2px;
    border-radius: @include border-raidus(4px);
    font-family: monospaces;
    @content
  }
}

p {
  @include code-inline {
    color: #33ccff;
    font-size: .8em;
  }
}
```
## 커스텀 함수
css 속성 정의의 모듈화와 재사용은 믹스인을 통해서 처리하면 된다. 함수는 어떤 값들을 사용해서 하나의 리턴값을 생성하는 용도로 사용하는 것이 좋다. 함수의 정의는 @function 지시어를 통해서 정의하며, 내부에서는 @return 지시어를 통해서 값을 내보낸다. 다음 예는 그리드 시스템에서 개별 셀과 여백의 크기를 통해서 n칸짜리 요소의 폭을 계산하는 함수이다.
```js
$grid-width: 40px; 
$gutter-width: 10px; 
@function grid-width($n) {
   @return $n * $grid-width + ($n -1 ) * $gutter-width; 
} 
#sidebar { width: grid-width(5); } // 믹스인과 달리 @include를 쓰지 않는다.
```
함수 역시 믹스인과 마찬가지로 복수 인자 및 인자 분해 등을 적용해서 사용할 수 있다. 또한 SASS 내에서는 여러 기본 함수들이 내장되어 있는데, 이에 대해서는 분량 조절 관계로 별도로 다루도록 하겠다.

## 흐름제어
함수나 믹스인을 작성할 때 특정 조건에 따른 분기나, 조건 혹은 연속열 (리스트 나 맵)의 각 원소에 대해 반복하는 등 흐름 제어와 관련된 기능을 사용해야 할 필요가 있다. 이 때 흐름제어 지시어들을 사용할 수 있다.

## 분기분
분기구문은 @if 절을 이용하여 작성한다. @if 표현식 { ... } @else if 표현식 { ... } @else { ... } 식으로 연결되는 다중 분기를 만들 수 있다.
```
@mixin hcolor($n) {
  @if $n % 2 == 0 { color: white; }
  @else { color: blue; } 
}
.row-3 { @include hcolor(3); } 

@function text-color($brightness) {
  @if $brightness < 128 { @return #333; }
  @return #ccc; 
}
code { color: text-color(200);
```

Sass의 @if 조건문에서 사용되는 논리(Boolean) 연산에는 ‘그리고’,’ 또는’, ‘부정’이 있습니다.
자바스크립트 문법에 익숙하다면 &&, ||, !와 같은 기능으로 생각하면 됩니다.

종류	설명 <br>
and	그리고 <br>
or	또는 <br>
not	부정(반대) <br>
간단한 예제를 확인하고, 더 자세한 내용은 조건문에서 살펴보겠습니다.

SCSS:
```
$width: 90px;
div {
  @if not ($width > 100px) {
    height: 300px;
  }
}
```
Compiled to:
```
div {
  height: 300px;
}
```
## 반복문
반복문은 크게 3가지로 나뉜다.

@for : n ~ m 까지의 숫자 범위에 대해 각 정수값에 대해 순회한다.
@each : 주어진 리스트나 맵의 각 원소에 대해 순회한다.
@while : 주어진 조건을 만족하는 동안 반복한다.
각각은 간단하게 예로 표현하겠다.
```
@for $i from 1 through 3 { // 1, 2, 3,에 대해 반복
  .time-#{$i} { width: 2em * $i; } 
} 

// 리스트 내 각 문자열 원소에 대해서... 
@each $animal in puma, sea-slug, egret, alamander {
  .#{$animal}-icon {
    background-image: url('/image/#{$animal}.png');   
  }
}

// 6, 4, 2번 아이템에 대해서 
$i : 6; 
@while $i > 0 {
  .item-#{$i} { width: 2em * $i }
  $i: $i - 2; 
}
```
여기서 소개하지 않은 몇 가지 기능들이 몇 가지 더 있는데 미디어 쿼리나 블럭 내에서 루트레벨 셀렉터 속성 지정하기, 플레이스 홀더를 사용한 지정문맥상속등이 있는데 흔히 쓰이는 기능은 아니어서 생략하도록 하겠다.

그외에 SASS에서 기본적으로 제공하는 내장함수들에 대해서는 별도로 살펴볼 필요가 있을 것이다. 특히 색상과 관련된 함수를 이용하면 별도의 그래픽 툴을 써서 색상값을 일일이 추출할 필요 없이 메인 색상으로부터 톤을 다양하게 변화시켜 사용하는데 활용할 수 있다.  그리고 리스트나 맵과 같은 자료 구조를 이용하면 더 많은 반복작업을 간단하게 처리하는데 도움이 될 수 있고, 이러한 기능들은 모두 기본 내장 함수에 의존하므로 그 때 그 때 찾아서 보도록 한다.
