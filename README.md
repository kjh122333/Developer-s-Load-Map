# Developer's Load Map


<!-- <details>
<summary>Front-end</summary>
<div markdown="1"> -->

> ***Learn the basics***
 - `HTML` : Hyper Text Markup Language, 웹 문서를 만들기 위해 사용하는 기본적인 웹 언어.
 - `CSS` : Cascading Style Sheets, 웹 문서의 전반적인 스타일을 미리 저장해 둔 스타일 시트.
 - `Javascript` : 객체지향 스크립트 언어, 크로스 플랫폼으로 **웹페이지의 동작** 을 담당
 	- `JQuery` : HTML의 클라이언트 사이드 조작을 단순화 하게끔 설계된 **Javascript 라이브러리**.
  
   ___위 3개(HTML, CSS, Javascript)가 웹사이트의 3가지 요소가 웹사이트 3대 구성 요소.___
  >>>
> ***Getting Deeper (1)***
 - `JavaScript`
	 - `ES6` : ECMA Script 6, 자바스크립트 언어의 표준입니다.
	 - Task Runners
	    - `npm scripts` : npm 사용시 필요한 스크립트
		 - `gulp` : (걸프)는 Fractal Innovations과 깃허브 오픈 소스 커뮤니티의 ***오픈 소스 자바스크립트 툴킷***으로, **프론트엔드 웹 개발의 스트리밍 빌드 시스템로 사용된다.Node.js와 npm 기반의 태스크 러너**이며, 소형화, 연결(concatenation), 캐시 버스팅(cache busting), 유닛 테스트, 린팅, 최적화 등 웹 개발에 수반되는 시간 소모적이고 반복되는 태스크들을 자동화하기 위해 사용된다.
		 - `Grunt` : 축소화, 컴파일, 유닛 테스트, 린트 등 주기적인 태스크들을 자동으로 수행하기 위해 사용되는 도구로서 **자바스크립트 태스크 러너**
	 - Package Manager
		 - `Yarn` : 하둡, 자바스크립트 패키지 매니저, npm의 핵심 이슈(보안성? 안정성?)을 해결하기위해 나옴.
		 - `npm` : (Node Package Manager)은 자바스크립트 프로그래밍 언어를 위한 패키지 관리자이다. 
	 - Choose a Framework
		 - `Angular` :  구글의 앵귤러 팀과 개인 및 기업 공동체에 의해 주도되는 타입스크립트 기반 오픈 소스 프론트엔드 웹 애플리케이션 프레임워크이다.
		 - `React` : 자바스크립트 라이브러리의 하나로서[2] 사용자 인터페이스를 만들기 위해 사용된다. 페이스북과 개별 개발자 및 기업들 공동체에 의해 유지보수된다
			 - `Flux` :  Facebook에서 클라이언트-사이드 웹 어플리케이션을 만들기 위해 사용하는 어플리케이션 아키텍쳐다. 단방향 데이터 흐름을 활용해 뷰 컴포넌트를 구성하는 React를 보완하는 역할을 한다.
			 - `Redux` : 가장 **사용률이 높은 상태관리 라이브러리** 입니다. 리덕스를 사용하면, 여러분이 만들게 될 컴포넌트들의 상태 관련 로직들을 다른 파일들로 분리시켜서 더욱 효율적으로 관리 할 수 있습니다. 
			 - `Mobx` : 인기있는 **리액트 상태 관리 라이브러리** 입니다. 
		 - `Vue.js` : Vue.js(간단히 Vue + 뷰 View)는 웹 애플리케이션의 사용자 인터페이스를 만들기 위해 사용하는 **오픈 소스 프로그레시브 자바스크립트 프레임워크** 
		 - `Ember JS` : **모델-뷰-뷰모델(MVV) 패턴**에 기반을 둔 **오픈 소스 자바스크립트 웹 프레임워크**
		 - `preact` : **표현 능력이 엄청난** 프레임워크, 리엑트의 **1/10** 크기
		 - `Inferno` : 클라이언트 서버 두 파트 모두 고성능 유저 인터페이스를 구축하기 위한 빠르고 반응 좋은 라이브러리	
	 - Testing
		 - `Jest` : Jest는 **페이스북**에서 만들어서 React와 더불어 많은 자바스크립트 개발자들로 부터 좋은 반응을 얻고 있는 **테스팅 라이브러리** 
		 - `Mocha` : 테스트 러너를 지원하는 테스트 프레임워크
		 - `Jasmine` : JavaScript 용 **오픈 소스 테스트 프레임 워크**. 
	 - Module Loader/Builder
		 - `Webpack` : **오픈 소스 자바스크립트 모듈 번들러**이다. 주로 자바스크립트를 위한 모듈 번들러이지만 호환 플러그인을 포함하는 경우 HTML, CSS, 심지어는 이미지와 같은 프론트엔드 자산들을 변환할 수 있다
		 - `rollup` : **자바 스크립트 모듈 번들러** ㅃ로 작은 코드를 라이브러리 또는 응용 프로그램과 같이 더 크고 복잡한 코드로 컴파일 가능
		 - `RequireJs / AMD`
		 - `Browserify`
	 - `TypeScript` : 타입스크립트(TypeScript)는 자바스크립트의 슈퍼셋인 오픈소스 프로그래밍 언어이다. 마이크로소프트에서 개발, 유지하고 있으며 엄격한 문법을 지원한다. C#의 리드 아키텍트이자 델파이, 터보 파스칼의 창시자인 Anders Hejlsberg가 개발에 참여한다.
	 - `Flow`
- `CSS`
	- `Responsive Web`
	- Choose Framework
		- `Foundation` : <span class="evidence">반응이 빠른 프론트 엔드 프레임 워크.</span> 활자체, 양식, 단추, 탐색 및 기타 인터페이스 요소는 물론 자바 스크립트 확장이 제공하는 선택적 기능을 포함 하여 반응 그리드 및 HTML 및 CSS UI 구성 요소, 템플릿 및 코드 스 니펫을 제공 합니다. Foundation 은 ZURB가 관리하며 오픈 소스 프로젝트
 	    - `Bootstrap` : <span class="evidence">웹사이트를 쉽게 만들 수 있게 도와주는 HTML, CSS, JS 프레임워크</span>
		- `Materialize CSS` : CSS, JavaScript 및 HTML로 작성된 UI 구성 요소 라이브러리
	    - `Semantic UI` : 웹페이지를 구축할 때 사용하는 라이브러리입니다. 여러 기능성을 가지고 있고, 매우 세련된 기본 디자인을 가지고 있기 때문에 웹페이지 구축에 큰 도움을 줍니다. 
	 - Reprocessors
 		- `Sass` : Sass(syntactically awesome stylesheets, 사스)는 햄튼 캐틀린이 설계하고 나탈리 바이첸바움이 개발한 스타일시트 언어,  종속형 시트(CSS)로 해석 및 컴파일되는 스크립트 언어
 		- `Less` : (Leaner Style Sheets, LESS, 레스)는 종속형 시트(CSS)로 컴파일한 다음 클라이언트 사이드나 서버 사이드에서 실행할 수 있는 동적 전처리기 스타일시트 언어이다.  Alexis Sellier가 설계한 Less는 Sass의 영향을 받았음.
 		- `Stylus` : 종속형 시트(CSS)로 컴파일되는 동적 스타일시트 전처리기 언어이다. 설계는 Sass와 LESS의 영향을 받았다. 4번째로 많이 쓰이는 CSS 전치리기 문법으로 간주된다. TJ Holowaychuk( Node.js의 이전 프로그래머이자 루나(Luna) 언어의 개발자 )에 의해 개발되었다. JADE와 Node.js로 작성되었다.
 		- `PostCSS` : **일상적인 CSS 동작을 자동화하기 위해 자바스크립트 기반 플러그인을 사용하는 소프트웨어 개발 도구** 이다. 이 도구는 위키백과, 페이스북, 깃허브의 코드를 개발하기 위해 사용되어 왔다. PostCSS는 npm 사용자들 간에 가장 선호되는 CSS 도구이다. Evil Martians의 프론트엔드 작업에서 아이디어를 가져와 Andrey Sitnik에 의해 설계됨.


> ***Getting Deeper (2)***
CSS
SVG
JavaScript
</div>
</details>

<details>
<summary>Back-end</summary>
<div markdown="1">


</div>
</details>
