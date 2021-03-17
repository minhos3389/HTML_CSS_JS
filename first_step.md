# HTML, CSS 그리고 JavaScript

## HTML
**HTML(Hyper Text Markup Language)**은 웹 페이지에 **제목, 문단, 표, 이미지, 동영상 등을 정의하고 그 구조와 의미를 부여하는 정적 언어로 웹의 구조를 담당**한다.
HTML으로 화면을 예쁘게 만들려고 시도하지 말자.(그렇게 하기도 어렵다.)
**튼튼한 구조(Semantic)**를 만드는 것에 집중해야 한다.

## CSS
**CSS(Cascading Style Sheets)**는 마크업 언어(HTML, XML 등)가 실제 표시되는 방법(색상, 크기, 폰트, 레이아웃 등)을 지정하여 **콘텐츠 구조를 꾸며주는 정적 언어**로 시각적인 표현을 담당한다. 예쁘게 만드는 것만 집중할 수 있다. 적당한 크기와 아름다운 색상, 원하는 위치를 지정하는데 집중할 수 있다.
스타일이 적용되는 방식이 Cascading(단계적으로) 된다고 해서 붙여진 이름. <br>
- 스타일(Style): html 문서의 글꼴이나 색상, 정렬, 배치 등의 겉모습을 결정짓는 내용들을 의미한다.
- 스타일 시트(Style Sheet): 스타일을 관리하기 쉽도록 한 군데 모아놓은 것을 의미한다.<br> Style Sheet을 사용하면 웹 페이지의 내용과 디자인을 분리해서 관리할 수 있어 편리하여 사용된다.

> cascade: 작은 폭포 , cascading (단계적인)

## JS 
JS(JavaScript)는 콘텐츠를 바꾸고 움직이는 등 페이지를 동적으로 꾸며주는 역할을 하는 프로그래밍 언어로 웹의 동적 처리를 담당한다.<br>
JS는 HTML과 CSS를 동원해서 그들의 업무(구조, 시각적 표현 등 )도 담당할 수 있지만, 그들보다는 잘하지 못하기 때문에(성능적으로) 되도록 동적처리에 집중한다.


### 웹 페이지를 제작할 때 각 언어의 역할을 다른 언어가 대체하지 않도록 주의하고, 각 역할이 제대로 수행되도록 구조적, 기술적으로 언어(코드)를 최적화 할 필요가 있다.

- 이 3가지의 단순한 역할을 하나하나 파일과 폴더별로 구분하는 이유는 규모가 크고 복잡한 웹 페이지를 만들 때 구조적, 기술적으로 최적화하는 과정이며 유지/보수, 확장성, 생산성 등을 위해서 꼭 필요하다. 

(https://html-css-js.com/)
---


## 웹 표준
웹 표준(Web Standard)이란 **‘웹에서 사용되는 표준 기술이나 규칙’**을 의미하며 W3C의 권고안에서 나온 기술들이 여기에 해당한다.
이 표준 기술들을 기준으로 웹 브라우저들(크롬, IE, 사파리 등)이 만들어지는데, 브라우저를 만드는 업체(구글, MS, 애플 같은)에서 표준 기술을 해석하는 차이, 새로운 기술 삽입(표준화 제정 단계에 따른) 등으로 조금은 다르게 구동되는 브라우저가 생기게 된다.
지금은 거의 사라졌지만 ActiveX, Flash 같은 기술은 표준이 아니다.

> W3C: World Wide Web Consortium ,  W3C는 회원기구, 정직원, 공공기관이 협력하여 웹 표준을 개발하는 국제 컨소시엄이다.<BR> 대부분의 경우 표준화 제정 단계의 ‘권고안 : W3C Recommendation(REC)’에 해당하는 기술을 표준이라고 생각하면 쉽다.

## 크로스 브라우징
![브라우저](https://heropy.blog/images/screenshot/html-css-starter/browsers.jpg)
> 구글 크롬, MS 엣지, 모질라 파이어폭스, 오페라, 이스트소프트 스윙, 네이버웨일, MS IE, 애플 사파리

크로스 브라우징(Cross Browsing)은 조금은 다르게 구동되는 여러 브라우저에서 **동일한 사용자 경험(같은화면 ,같은 동작 등)**을 줄 수 있도록 제작하는 기술, 방법 등을 의미한다.<BR>
대부분의 브라우저는 최대한 웹 표준을 준수하여 제작되기 때문에 문제가 적으나 MSIE는 제멋대로 만들어진 경향이 있어 문제가 많았다. <BR>
IE에서도 동작하게 하는 것을 크로스 브라우징이라고 부르기도 한다. (하지만 IE 곧 **종료**된다..)

## 웹 접근성
웹 접근성이란 정상적인 웹 콘텐츠 사용이 가능한 일반 사용자부터 고령자, 장애인 같은 신체적, 환경적 조건에 제한이 있는 사용자를 포함해 **모든 사용자들이 접근할 수 있는 웹 콘텐츠를 제작하는 방법**을 말한다. 청각 장애인을 위해 영상에 자막을 넣거나, 마우스를 사용할 수 없는 사람들을 위해 키보드를 통해서도 웹을 이용할 수 있게 하거나(혹은 그 반대), 이미지에 대체 텍스트를 제공하는 간단한 방법들까지 모두 웹 접근성에 해당한다.

- 웹 접근성 연구소(https://www.wah.or.kr:444/Accessibility/define.asp)
- 한국형 웹 콘텐츠 접근성 지침(https://www.wah.or.kr:444/Participation/guide.asp)
- 웹 콘텐츠 제작기법(https://www.wah.or.kr:444/Participation/technique.asp)

### 정보 통신 보조기기
장애인의 경우 정보 통신 보조기기를 통해 웹 콘텐츠에 접근할 수 있어야 한다.
- 한손 사용자용 키보드 : 편마비 장애인을 위해 한손으로 타이핑하게 디자인되어있는 키보드
- 큰 키 키보드 : 키보드의 입력 버튼을 크게 만들어 손 떨림이나 상지 기능에 장애가 있는 분에게 적합하며, 키가드가 있어 오타를 방지할 수 있는 특수 키보드
- n-Abler 조이스틱 : 팔의 움직임이 원활하지 못해 일반 마우스를 사용하기 어려운 분들을 위한 조이스틱 마우스
- SmartNav : 상지 및 하지를 사용하기 어려운 분들이 머리의 움직임을 통해(적외선 및 난반사 스티커 활용) 컨트롤할 수 있는 특수 마우스
- 소리알리미 : 소리 정보를 불빛과 진동으로 알려주는 청각장애인용 무선신호기

### 웹 접근성 품질인증 마크
![웹접근성품질인증마크](https://heropy.blog/images/screenshot/html-css-starter/web_access_mark.jpg)
장애인 및 고령자가 웹 사이트 이용에 불편이 없도록 웹 접근성 표준을 준수한 우수 사이트에 대해 품질을 인증하고 마크를 부여하는 제도로써 
「국가정보화기본법」제32조의2 및 동법 시행규칙 제3조의3에 의거 과학기술정보통신부가 지정한 웹 접근성 품질인증 기관을 통해 심사 및 인증을 받을 수 있다.<br>
서면 심사와 기술 심사 등을 거쳐 페이지 수에 따라 기본 100만원 이상의 심사 비용을 지불해야 한다.

> 비용 및 기술 측면에서 현실적으로 개인이나 중소기업 사이트에서 획득 어렵다.

<BR>
<BR>

# 웹 개발을 위한 에디터

### HTML, CSS, JS를 위한 웹 개발(프론트엔드, Node.js) 에디터 중 실무에서 많이 사용되는 크로스 플랫폼(Windows, macOS) 에디터들

## Sublime Text
: 상대적으로 가볍고 성능 저하가 적다. 무료

## Atom
: 깃헙(Github)에서 만든 텍스트 에디터다. 확장 기능도 충분하고 외국에서 인기가 많다. macOS에서는 문서 작업 시 자주 사용된다. 무료

## Brackets
: 어도비(Adobe)에서 만든 텍스트 에디터 <br> Creative Cloud 제품군이 아니고 오픈소스로 풀려 있다. <br> Live Preview 기능이 기본으로 제공되는 등
시각적인 결과물을 확인하는데 특화되어 있으나 확장기능이나 성능 최적화에 대해선 아쉽다. 무료

## VS Code
: VS Code(Visual Studio Code)는 마이크로 소프트(MS)에서 만든 텍스트 에디터이다.
<BR>확장기능이 많고 가볍다. 무료

## WEBStorm
: JetBrain에서 만든 통합 개발 환경(IDE) 프로그램 중 하나.
별도의 확장 기능이 거의 필요하지 않으며 대부분의 프로젝트를 바로 시작할 수 있다.
편한 권장 프로그램이지만 유료. (학생 라이선스를 얻으면 무료)

> 구독형 프로그램은 개인 라이선스 기준 1년 $59.


---

## 이미지에 대한 이해

### 웹에서 사용하는 이미지
: 이미지(그래픽)는 크게 ```<비트맵>```과 ```<벡터>```로 구분된다.

- 비트맵(Bitmap)은 각 픽셀이 모여 만들어진 정보의 집합으로 레스터(Raster)이미지라고도 부른다.
    - 픽셀 단위로 화면에 렌더링한다. (렌더링: 컴퓨터가 화면에 그림을 그려서 우리가 볼 수 있게 한다.) 사이트를 렌더링한다. 
    이렇게 표현 화면에 그려져서 우리눈에 보이게된다는 의미.
    - 우리가 일반적으로 사용하는 대부분의 이미지가 비트맵 형식이다.(jpg,png,gif,webp(webp는 구글에서만듦)등)
    - 그림판, 포토샵과 같은 툴로 편집할 수 있다.

- 벡터(Vector)는 수학적 정보의 형태(Shape)들이 만들어내는 결과물이다.
    - 이미지가 가지고 있는 점, 선, 면의 위치(좌표), 색상 등의 정보를 온전히 가지고 있으며 그를 화면에 렌더링합니다.
    - 따라서 좀 더 많은 연산을 해야 하지만, 대신 해상도(픽셀)에 영향을 비트맵 이미지와 달리 해상도로부터 자유롭게 렌더링할 수 있습니다.
    - 쉽게 말하면 확대 축소를 해도 이미지가 꺠지지 않습니다.
    - 또한 수학적 정보만을 가지고 있기 때문에 이미지 확대/축소에 따른 용량 변화가 없습니다. 장점이될수도 단점이 될수도있습니다.
    - 일러스트 같은 툴로 편집할 수 있습니다.


|이미지 종류|  장점                       |단점|
|:--|:--|:--|
|비트맵   |  정교하고 다양한색상 자연스럽게 표현. |    확대/축소 시 계단현상, 품질 저하|
|벡터     | 확대/축소에서 자유로움, 용량변화가 없음. | 정교한 이미지(인물,풍경 사진 같은)를 표현하기 어려움.|

- Sketch 3는 이미지의 편집보단 벡터 기반의 UI 제작 툴이라고 볼 수 있다.


## JPG,PNG,GIF,WEBP,SVG

### JPG(JPEG)

JPG는 Joint Photographic coding Experts Group Full-color와 Gray-scale의 압축을 위해 만들어졌으며 압축률이 훌륭해 사진이나 예술분야에서 많이 사용된다.
- 손실압축(여러번원본저장하므로 주의, 대신 용량적게든다.)
- 표현 색상도(24비트, 약 1600만색상)뛰어나 고해상도표시장치에 적합하다.
- 이미지의 품질과 용량을 쉽게 조절 가능하다.
- 가장 널리 쓰이는 이미지 포맷이다.
- 높은 압축률(적은 용량)에 적합하다.


### PNG

PNG(Portalbe Network Graphics)는 Gif의 대체 포맷으로 개발되었다.
- 비손실압축
- 8비트(256색상)/ 24비트(약1600만 색상)컬러 이미지 처리 지원
- Alpha Channel지원(투명도 지원/jpg는 못한다.)
- W3C 권장 포맷.
- ```투명도 지원``` 

> 어떤 이미지를 웹에서 쓰지 생각들면 그냥 png 쓰는게 안전하다.

### GIF
GIF(Graphics Interchange Format)는 이미지 파일 내에 이미지 및 문자열 같은 정보들을 저장할 수 있다.
- 비손실압축
- 여러장의 이미지를 한 개의 파일에 담을 수 있음(움짤, 애니메이션)
- 8비트 컬러만 지원(다양한 색상을 표현하는 작업에는 적합하지 않다.
- 동영상 같은 이미지(애니메이션)


> 웹에서 가장 많이 사용된느 세가지 포맷을 알아보았다.<br>
용량을 줄여서 사용하고 싶을경우 -> jpg <br>
이미지의 투명도가 필요하다 -> png(ALpha channel 지원) <br>
애니메이션 지원 -> GIF <br>
	
### WEBP
JPG, PNG, GIF를 모두 대체할 수 있는 구글이 개발한 이미지 포맷.
- 완벽한 손실/비손실 압축 지원
- GIF같은 애니메이션 지원
- Alpha Channel지원
- 완벽한 포맷이나, 지원 브라우저가 제한적이다.  아직 환경이 완전하게 맞춰지지 않았다.

(https://caniuse.com/webp)
Can i use 닷컴에서 지원되는 브라우저 확인할 수 있다. 


### SVG
SVG(Scalable Vector Graphics)는 마크업 언어(HTML/XML)기반의 벡터 그래픽을 표현하는 포맷이다.

- 해상도의 영향에서 자유로움
- CSS로 Styling 가능
- JavaScriptfh EventHandling 가능
- 코드 혹은 파일로 사용 가능

벡터 이미지에 익숙하지 않다면 다루기 조금 까다로울 수 있다. <br>
파일로도 , 코드로도 표현할 수 있다.<br>
일러스트프로그램으로 벡터이미지로 내보내기를 통해서 벡터 이미지로 가져올 수 있다. <br>
코드로 활용해서 쓸 수 있으나 프로그램없으면 솔직히 불가능.(svg파일저장해서 vscode에서 열어보면 코드 많고 중구남방이라알수없음)

### 특수 문자 용어 정리

|기호	|영어(발음)	|한글|
|:--|:--|:--|
|`|	Grave(그레이브)|	-|
|~|	Tilde(틸드)|	물결표시|
|!|	Exclamation(엑스클러메이션) mark|	느낌|
|@|	At(엣) sign	골뱅이|
|#|	Number(넘버) sign, Sharp(샵)|	샵, 우물 정|
|$|	Dollar(달러) sign|	달러|
|%|	Percent(퍼센트) sign|	퍼센트|
|^|	Caret(캐럿)|	-|
|&|	Ampersand(엠퍼센드)|	-|
|*|	Asterisk(에스터리스크)|	별표|
|-|	Hyphen(하이픈), Dash(대쉬)|	마이너스|
|_|	Underscore(언더스코어), Low dash(로대쉬)|	밑줄|
|=|	Equals(이퀄) sign|	이꼬르|
|“|	Quotation(쿼테이션) mark|	큰 따옴표|
|‘|	Apostrophe(아포스트로피)|	작은 따옴표|
|:|	Colon(콜론)	|땡땡이|
|;|	Semicolon(세미콜론)|	털 달린 땡땡이|
|,|	Comma(콤마)	|쉼표|
|.|	Period(피리어드), Dot(닷)	|점, 마침표|
|?|	Question(퀘스천) mark	|물음표|
|/|	Slash(슬래쉬)|	-|
|```\```|	Backslash(백슬래쉬)|-|
|()|	Parenthesis(퍼렌서시스)|	(소)괄호|
|{}|	Brace(브레이스)	|중괄호|
|[]|	Bracket(브래킷)	|대괄호|
|<>|	Angle Bracket(앵글 브래킷)|	꺽쇠괄호|

> 특수기호 및 아스키코드정보.
(https://www.freeformatter.com/html-entities.html)

이렇게 자주 표현하게 된다.  <br>
특수기호로 변환. 키보드로 직접적으로 입력했을 때 코드작동하지않는경우가 있을 수 있다.<br>
그래서 특수기호로 변환해서 사용하는 경우가 많다.<br>
(파이썬 웹 Django할때도 이거썼었는데,,)

```<``` = ```&lt;```
```>``` = ```&gt;```


---

## 오픈소스

## 오픈소스 라이선스

**오픈소스** 란 어떤 제품을 개발하는 과정에 필요한 소스코드나 설계도를 누구나 접근해서 열람할 수 있도록 공개하는 것. <br>
오픈소스에는 저작권이 붙어있다. 라이선스를 확인하지 않으면 비용지불 할 수도있다.<br>
오픈소스중에서도 무료로 활용할 수 있는 오픈소스를 찾는것이 중요하다.(개인적으로도 상업적으로도무료로 활용할 수 있는지 확인하는 것이 중요하다.)
<br>
현실적으론 처음부터 끝까지 모든 코드를 직접 작성할 수 없기 때문에 많은 경우 오픈소스에 의존하게 된다.<br>
개인적인 사용을 목적으로 문제가 없겠지만, 회사에서 (상업적으로)아무 생각 없이 사용하다가는 문제가 되어 해고당하거나 피해보상을 해줘야 할 수 있다.<br>
물론 인터넷에 떠도는 코드 몇 줄 복사해 썼다고 그 정도 심각한 문제가 되진 않겠지만, 항상 조심하는 것이 좋다.<br>
회사에서 작업 중에 괜찮은 오픈 소스를 찾았다면 반사적으로 License부터 찾도록 하자.

> 보기만 해도 흐뭇해지는 라이선스들

### Apache License
: 아파치 소프트웨어 재단에서 자체 소프트웨어에 적용하기 위해 만든 라이선스다.<br>
  개인적/상업적 이용, 배포, 수정, 특허 신청이 가능하다.
  
### MIT License
: 메사추세츠공과대학(MIT)에서 소프트웨어 학생들을 위해 개발한 라이선스다.<br>
  개인 소스에 이 라이선스를 사용하고 있다는 표시만 지켜주면 되며, 나머지 사용에 대한 제약은 없기 때문에 인기가 많다.
  
### BSD License
: BSD(Berkeley Software Distribution)는 버클리 캘리포니아대학에서 개발한 라이선스다. <br>
  MIT와 동일하게 라이선스 표기만 지켜주시면 된다.
  
### Beerware
: 오픈소스 개발자에게 맥주를 사줘야 하는 라이선스입니다.*재밌는라이센스 굳이 명분을 붙인거고 사실상 공짜.<br>
  물론 만날 수 있다면 말이다.
  
그 외 더 많은 오픈소스라이선스에 대한 정보는 ```OpenSource.org``` 에서 확인할 수 있다.