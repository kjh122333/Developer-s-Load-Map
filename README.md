# Developer's Load Map


<details>
<summary>Front-end</summary>
<div markdown="1">
	
> ***Learn the basics***
 - `HTML` : Hyper Text Markup Language, 웹 문서를 만들기 위해 사용하는 기본적인 웹 언어.
 - `CSS` : Cascading Style Sheets, 웹 문서의 전반적인 스타일을 미리 저장해 둔 스타일 시트.
 - `Javascript` : 객체지향 스크립트 언어, 크로스 플랫폼으로 **웹페이지의 동작** 을 담당
 	- `JQuery` : HTML의 클라이언트 사이드 조작을 단순화 하게끔 설계된 **Javascript 라이브러리**.
  
   > 위 3개(HTML, CSS, Javascript)가 웹사이트의 3가지 요소가 웹사이트 3대 구성 요소.
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
	 - `TypeScript` : 타입스크립트(TypeScript)는 자바스크립트의 슈퍼셋인 오픈소스 프로그래밍 언어이다. 마이크로소프트에서 개발, 유지하고 있으며 엄격한 문법을 지원한다. C#의 리드 아키텍트이자 델파이, 터보 파스칼의 창시자인 Anders Hejlsberg가 개발에 참여한다.[1] 클라이언트 사이드와 서버 사이드를 위
	 - `Flow`
CSS
> ***Getting Deeper (2)***
CSS
SVG
JavaScript
</div>
</details>
## Back-end
