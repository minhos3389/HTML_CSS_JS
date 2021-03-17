# VS Code 

## VS Code 인터페이스
![interface](https://heropy.blog/images/screenshot/html-css-starter/vs_code_interface.jpg)

## 확장 기능(Extensions)
다른 에디터도 동일하지만 VS Code는 확장 기능을 제공하며 최초 설치한 버전에서 제공하지 않는 다양한 확장기능들을 설치(다운로드)해서 사용할 수 있다.
에디터의 버전업 과정에서 자체적으로 흡수하는 기능도 있을 수 있으므로 몇몇 확장 가능은 에디터의 버전에 따라 이미 지원하고 있을 수 있으니 해당 기능이
제공되는지 확인하고 설치한다.

### Korean Language Pack for Visual Studio Code

VS Code의 거의 모든 메뉴를 한국어로 변경한다.

### Beautify 

코드 가독성을 위해 코드 작성 스타일을 (아름답게) 수정한다. <br>  입문자들에게 추천된다.

1. Preferences > Keyboard
2. HookyQR.beautify를 검색(HookyQR.beautifyFile 아니에요!)
3. 키 바인딩 선택
4. 원하는 단축키 등록

> "Alt + Ctrl + L"(Windows) / "Alt + Cmd + L" (macOS)을 추천

### Live Server
하단 상태 바(Status bar)에서 Go Live 선택 또는, HTML 화면에서 우클릭 > Open with Live Server 선택

> VS Code 최신버전은 이미 설치되어 있다.

### Auto Rename Tag
태그 이름을 수정할 때 열린 태그와 닫힌 태그가 쌍으로 수정된다. <br> 각각 수정하는 번거로움 줄인다.

## 그 외 추천

### Terminal
하단 상태 바에 Terminal 로고 생성 및 마우스 오른쪽 버튼 Open in integerated Terminal 가능, ctrl + Alt + O 단축키 터미널 실행 가능
### Live Saas Compiler
(https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
### Turbo Console log 
(https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
Insert meaningful log message automatically
1. Selecting the variable which is the subject of the debugging
2. Pressing ctrl + alt + L
(The log message will be inserted in the next line relative to the selected variable)
### Better Comments
(https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
### Highlight Matching Tag
각각의 태그의 시작과 끝에 하이라이트 효과를 준다. <br>
(https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)

### GitLens
(https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
### REST Client
(https://marketplace.visualstudio.com/items?itemName=humao.rest-client)


## 알아두면 좋은 단축키

### Preferences > Keyboard Shortcut(바로가기 키) 에서 단축키를 확인하거나 변경할 수 있다.

>" 를 사용하면 키 바인딩을 검색할 수 있다. <br>
" 를 닫으면 정확한 검색을 요구하므로 "cmd + p 와 같이 "를 닫지 않고 검색하는 것을 추천한다.

|Windows 단축키|설명|
|:-:|:-:|
|"Ctrl + B" |사이드바 열기/닫기|
|"Ctrl + P"|빠른 열기(파일이나 기호 탐색)|
|"Ctrl + Shift + P"|모든 명령 표시(에디터의 모든 명령에 접근)|
|"Ctrl + F"|찾기(검색)|
|"Ctrl + H"|찾기(검색)/바꾸기(대체)|
|"Alt + Up"|줄 위로 이동|
|"Alt + Down"|줄 아래로 이동|
|"Shift + Alt + UpArrow"|위에 줄 복사|
|"Shift + ALt + DownArrow"|아래 줄 복사|
|"Tab"|들여쓰기|
|"Shift + Tab"|내어쓰기|
|"Ctrl + PageUp"|이전 편집기 열기(좌측 창으로 전환)|
|"Ctrl + PageDown"|다음 편집기 열기(우측 창으로 전환)|
|"Ctrl + \"|편집기 분할(백슬래쉬)|
|"Ctrl + 숫자"|```숫자```번째 분할된 편집기 그룹에 포커스|
|"Ctrl + W"|편집기 닫기|

### 약어로 랩핑 (Wrap)
1. 랩핑할 코드 선택
2. 모든 명령 표시 실행 / "Ctrl + Shift + P"(Windows), "Cmd + Shift + P"(macOS)
3. ```Emmet: Wrap with Abbreviation(Emmet: 약어로 랩핑)```를 입력하거나 목록에서 선택("Enter")
4. ```div```, ```span``` 등의 Emmet 문법 (ex: ```.wrapper```,```sapn.bold```)을 입력
5. 완료("Enter").
