# Developer's Load Map

<details>
<summary>Front-end</summary>
<div markdown="1">

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
     - `TypeScript` : 컴파일 언어, 정적 타입 언어, 링킹 과정이 생략되어 있다. 자바스크립트의 슈퍼셋인 오픈소스 프로그래밍 언어이다. 마이크로소프트에서 개발, 유지하고 있으며 엄격한 문법을 지원한다. C#의 리드 아키텍트이자 델파이, 터보 파스칼의 창시자인 Anders Hejlsberg가 개발에 참여한다
     - `Flow`
- `CSS`
    - `Responsive Web` (즉각 반응 웹)
    - Choose Framework
        - `Foundation` : 반응이 빠른 프론트 엔드 프레임 워크. 활자체, 양식, 단추, 탐색 및 기타 인터페이스 요소는 물론 자바 스크립트 확장이 제공하는 선택적 기능을 포함 하여 반응 그리드 및 HTML 및 CSS UI 구성 요소, 템플릿 및 코드 스 니펫을 제공 합니다. Foundation 은 ZURB가 관리하며 오픈 소스 프로젝트
        - `Bootstrap` : 웹사이트를 쉽게 만들 수 있게 도와주는 HTML, CSS, JS 프레임워크
        - `Materialize CSS` : CSS, JavaScript 및 HTML로 작성된 UI 구성 요소 라이브러리
        - `Semantic UI` : 웹페이지를 구축할 때 사용하는 라이브러리입니다. 여러 기능성을 가지고 있고, 매우 세련된 기본 디자인을 가지고 있기 때문에 웹페이지 구축에 큰 도움을 줍니다. 
     - Preprocessors(전처리 장치)
        - `Sass` : Sass(syntactically awesome stylesheets, 사스)는 햄튼 캐틀린이 설계하고 나탈리 바이첸바움이 개발한 스타일시트 언어,  종속형 시트(CSS)로 해석 및 컴파일되는 스크립트 언어
        - `Less` : (Leaner Style Sheets, LESS, 레스)는 종속형 시트(CSS)로 컴파일한 다음 클라이언트 사이드나 서버 사이드에서 실행할 수 있는 동적 전처리기 스타일시트 언어이다.  Alexis Sellier가 설계한 Less는 Sass의 영향을 받았음.
        - `Stylus` : 종속형 시트(CSS)로 컴파일되는 동적 스타일시트 전처리기 언어이다. 설계는 Sass와 LESS의 영향을 받았다. 4번째로 많이 쓰이는 CSS 전치리기 문법으로 간주된다. TJ Holowaychuk( Node.js의 이전 프로그래머이자 루나(Luna) 언어의 개발자 )에 의해 개발되었다. JADE와 Node.js로 작성되었다.
        - `PostCSS` : **일상적인 CSS 동작을 자동화하기 위해 자바스크립트 기반 플러그인을 사용하는 소프트웨어 개발 도구** 이다. 이 도구는 위키백과, 페이스북, 깃허브의 코드를 개발하기 위해 사용되어 왔다. PostCSS는 npm 사용자들 간에 가장 선호되는 CSS 도구이다. Evil Martians의 프론트엔드 작업에서 아이디어를 가져와 Andrey Sitnik에 의해 설계됨.


> ***Getting Deeper (2)***

 - `CSS`

    - Methodologles : css 아키텍처
       - `SUITCSS`
       - `BEM`
      - `OOCSS`
      - `SMACSS`
      - `Systematic CSS`
      - `Dive Deep CSS3` : https://estelle.github.io/cssdeepdive/#slide1
 - `SVG`
   - `D3` : D3 또는 Data-Driven Documents)는 웹브라우저 상에서 동적이고 인터렉티브한 정보시각화를 구현하기 위한 자바스크립트 라이브러리
 - `Javascript`
   - `Design Patterns` : 객체 지향 프로그래밍 설계를 할 때 자주 발생하는 문제들을 피하기 위해 사용되는 패턴.
        <details>
        <summary>종류</summary>
        <div markdown="1">

        1. `반복자 (Iterator)` : 내부 표현부를 노출하지 않고 어떤 객체 집합에 속한 원소들을 순차적으로 접근할 수 있는 방법을 제공하는 패턴이다.
        2. `적응자(Adapter)` : 클래스의 인터페이스를 사용자가 기대하는 다른 인터페이스로 변환하는 태펀으로, 호환성이 없는 인터페이스 때문에 함께 동작할 수 없는 클래들이 함께 작동하도록 한다.
        3. `템플릿 메소드 (Template Method)` : 객체의 연산에는 알고리즘의 뼈대만을 정의하고 각 단계에서 수행할 구체적 처리는 서브클래스 쪽으로 미루는 패턴이다. 알고리즘의 구조 자체는 그대로 놔둔 채 알고리즘 각 단계의 처리를 서브클래스에서 재정의할 수 있게 한다.
        4. `팩토리 메서드 (Factory Method)` : 객체를 생성하는 인터페이스는 미리 정의하되, 인스턴스를 만들 클래스의 결정은 서브클래스 쪽에서 내리는 패턴이다. 팩토리 메소드 패턴에서는 클래스의 인스턴스를 만드는 시점을 서브클래스로 미룬다.
        5. `단일체 (Singleton)` : 어떤 클래스의 인스턴스는 오직 하나임을 보장하며, 이 인스턴스에 접근할 수 있는 전역적인 접촉점을 제공하는 패턴이다.
        6. `원형(Prototype)` : 생성할 객체의 종류를 명세화하는 데에 원형이 되는 예시물을 이용하고, 그 원형을 복사함으로써 새로운 객체를 생성하는 패턴이다
        7. `빌더(Builder)` : 복합 객체의 생성 과정과 표현 방법을 분리하여 동일한 생성 절차에서 서로 다른 표현 결과를 만들 수 있게 하는 패턴
        8. `추상 팩토리(Abstract Factory)` : 구체적인 클래스를 지정하지 않고 관련성을 갖는 객체들의 집합을 생성하거나 서로 독립적인 객체들의 집합을 생성할 수 있는 인터페이스를 제공하는 패턴
        9. 가교(Bridge) : 구현부에서 추상층을 분리하여 각자 독립적으로 변형할 수 있게 하는 패턴
        10. `전략 (Strategy)` : 동일 계열의 알고리즘군을 정의하고, 각각의 알고리즘을 캡슐화하며, 이들을 상호교환이 가능하도 록 만드는 패턴이다. 알고리즘을 사용하는 사용자와 상관없이 독립적으로 알고리즘을 다양하게 변경할 수 있게 한다.
        11. `복합체(Composite)` : 객체들의 관계를 트리 구조로 구성하여 부분-전체 계층을 표현하는 패턴으로 사용자가 단일 객체와 복합 객체 모두 동일하게 다루도록 한다
        12. `장식자(Decorator)` : 주어진 상황 및 용도에 따라 어떤 객체에 책임을 덧붙이는 패턴으로, 기능 확장이 필요할 때 서브클래싱 대신 쓸 수 있는 유연한 대안이 될 수 있다.
        13. `방문자 (Visitor)` : 객체 구조를 이루는 원소에 대해 수행할 연산을 표현하는 패턴으로, 연산을 적용할 원소의 클래스를 변경하지 않고도 새로운 연산을 정의할 수 있게 한다
        14. `책임 연쇄(Chain of Responsibility)` : 요청을 처리할 수 있는 기회를 하나 이상의 객체에 부여하여 요청을 보내는 객체와 그 요청을 받는 객체 사이의 결합을 피하는 패턴, 요청을 받을 수 있는 객체를 연쇄적으로 묶고, 실제 요청을 처리한 객체를 만날 때까지 객체 고리를 따라서 요청을 전달한다.
        15. `퍼사드 (Facade)` : 서브시스템에 있는 인터페이스 집합에 대해서 하나의 통합된 인터페이스를 제공하는 패턴으로, 서브시스템을 좀더 사용하기 편하게 만드는 상위 수준의 인터페이스를 정의한다.
        16. `중재자 (Mediator)` : 한 집합에 속해있는 객체들의 상호작용을 캡슐화하는 객체를 정의하는 패턴이다, 객체들이 직접 서로를 참조하지 않도록 함으로써 객체들 사이의 소결합(loose coupling)을 촉진시키며, 개발자가 객체들의 상호작용을 독립적으로 다양화시킬 수 있게 만든다.
        17. `감시자 (Observer)` : 객체 사이에 일 대 다의 의존 관계를 정의해 두어, 어떤 객체의 상태가 변할 때 그 객체에 의존성을 가진 다른 객체들이 그 변화를 통지받고 자동으로 갱신될 수 있게 만드는 패턴이다.
        18. `메멘토 (Memento)` : 캡슐화를 위배하지 않는 채 어떤 객체의 내부 상태를 잡아내고 신체화시켜, 이후에 해당 객체가 그 상태로 다시 되돌아올 수 있도록 하는 패턴이다.
        19. `상태 (State)` : 객체의 내부 상태에 따라 스스로 행동을 변경할 수 있게끔 허가하는 패턴으로, 이렇게 하면 객체는 마치 자신의 클래스를 바꾸는 것 처럼 보인다.
        20. `플라이급 (Flyweight)` : 크기가 작은객체가 여러개 있을 때, 공유를 통해 이들을 효율적으로 지원하는 패턴이다.
        21. `프록시 (Proxy)` : 어떤 다른 객체로 접근하는 것을 통제하기 위해서 그 객체의 대리자(surrogate), 또는 자리채움자(placeholder)를 제공하는 패턴이다.
        22. `명령(Command)` : 요청을 객체의 형태로 캡슐화하여, 서로 요청이 다른 사용자의 매개변수화, 요청 저장 또는 로깅, 그리고 여난의 취소를 지원하게 만드는 패턴
        23. `해석자 (Interpreter)` : 주어진 언어에 대해, 그 언어의 문법을 위한 표현 수단을 정의하고, 이와 아울러 그 표현 수단을 사용하여 해당 언어로 작성된 문장을 해석하는 해석기를 정의하는 패턴이다



        출처: https://88240.tistory.com/227 [shaking blog]

        </div>
        </details>



    - `Regex` : 정규식, https://developer.mozilla.org/ko/docs/Web/JavaScript/Guide/%EC%A0%95%EA%B7%9C%EC%8B%9D
    - `GOF Design Patterns`: GoF(Gang of Fout)라 불리는 사람들, 에리히 감마(Erich Gamma), 리차드 헬름(Richard Helm), 랄프 존슨(Ralph Johnson), 존 블리시디스(John Vissides)
소프트웨어 개발 영역에서 디자인 패턴을 구체화하고 체계화한 사람들
23가지의 디자인 패턴을 정리하고 각각의 디자인 패턴을 생성(Creational), 구조(Structural), 행위(Behavioral) 3가지로 분류했다.
Creational Pattern
객체를 생성하는데 관련된 패턴들
객체가 생성되는 과정의 유연성을 높이고 코드의 유지를 쉽게 함
Structural Pattern
프로그램 구조에 관련된 패턴들
프로그램 내의 자료구조나 인터페이스 구조 등 프로그램의 구조를 설계하는데 활용할 수 있는 패턴들
Behavioral Pattern
반복적으로 사용되는 객체들의 상호작용을 패턴화 해놓은 것들
    - `Learn different testing techniques` : https://www.leaseweb.com/labs/2013/12/testing-techniques-better-manual-testing/

</div>
</details>

<details>
<summary>Back-end</summary>
<div markdown="1">

 - `Ruby` : 루비는 **마츠모토 유키히로** 가 개발한 **동적 객체 지향 스크립트 프로그래밍 언어** 루비는 **순수 객체 지향 언어** 라, 정수나 문자열 등을 포함한 데이터 형식 등 모든 것이 객체임
	- Package Manager
		- `RubyGems` : 루비 프로그래머는 gem을 **이용해서 간단하게 원하는 프로그램을 설치할 수** 있으며, 자신이 개발한 프로그램을 간단하게 배포할 수 있다, 루비에서 지원하는 **패키지 시스템( =라이브러리)**, cf) node에서 사용하는 npm과 유사
	- Framework
		- `Sinatra` :  최소한의 노력으로 루비 기반 웹 애플리케이션을 신속하게 만들 수 있게 해 주는 DSL(도메인 특화 언어))
		- `Ruby on Rails` :  루비로 작성된 MVC 패턴을 이용하는 오픈 소스 웹 프레임워크이다. 줄여서 레일즈라 불리기도 함
	- Testing
		- `RSpec` : Ruby 코드를 테스트하기 위해 Ruby 로 작성된  **도메인 특정 언어(DSL) 테스트 도구** 
	- `ByeBug`
	


	- Package Manager
		- `Pip` :  파이썬으로 작성된 패키지 소프트웨어를 설치 · 관리하는 **패키지 관리 시스템** 이다. Python Package Index (PyPI)에서 많은 파이썬 패키지를 찾을 수 있다
	- Framework - Sync
		- `Pyramid` :  작고 빠르고 개방적이며 **오픈 소스 Python 웹 프레임 워크**
		- `Flask` : 파이썬으로 작성된 **마이크로 웹 프레임워크** 의 하나로, Werkzeug 툴킷과 Jinja2 템플릿 엔진에 기반을 둔다. BSD 라이선스이다.
		- `Django` : 파이썬으로 작성된 **오픈 소스 웹 애플리케이션 프레임워크** 로, 모델-뷰-컨트롤러(MVC) 패턴을 따르고 있다. 
	- Testing
		- `doctest` : Python 프로그래밍 언어의 표준 라이브러리에 포함 된 **모듈** 로, *표준 파이썬 인터프리터 쉘의 출력을 기반으로 테스트를 쉽게 생성*하고 문서 문자열에 잘라 붙여 넣을 수 있습니다.
		- `py.test` : pytest는 더 나은 프로그램을 작성하는 데 도움이되는 완성 된 완전한 기능을 갖춘 Python 테스트 도구입니다.
		- `unittest / pyUnit` : Python에 포함된 다양한 테스트를 자동화할 수 있는 기능이 포함되어 있는 **표준 라이브러리**
	- Async
		- `Tornado` :  작성된 확장 성 있고 비 차단 웹 서버 및 웹 응용 프로그램 프레임 워크 입니다 . [2] FriendFeed 에서 사용하기 위해 개발되었습니다
		- `gevent` : libev(이벤트 루프를 기반으로하는 비동기 I / O를 지원하는 다중 플랫폼 C 라이브러리)기반의 동시성 **라이브러리** 입니다. gevent는 동시성과 네트워크 관련 작업들을 위한 다양한 API를 제공
		- `aiohttp` : Python 3.4부터 표준 라이브러리로 추가된 asyncio (PEP3156) 를 위한 HTTP **서버/클라이언트 프레임워크** 이다
		

- 번외
	- 미들웨어 : 양 쪽을 연결하여 데이터를 주고 받을 수 있도록 중간에서 매개 역할을 하는 소프트웨어, 네트워크를 통해서 연결된 여러 개의 컴퓨터에 있는 많은 프로세스들에게 어떤 서비스를 사용할 수 있도록 연결해 주는 소프트웨어를 말한다. 3계층 클라이언트/서버 구조에서 미들웨어가 존재한다. 웹 브라우저에서 데이터베이스로부터 데이터를 저장하거나 읽어올 수 있게 중간에 미들웨어가 존재하게 된다.
	- TDD(Test Driven development)란 매우 짧은 개발 사이클을 반복하는 소프트웨어 개발 프로세스 중 하나입니다. JUnit(Java), pyUnit(python), qUnit(javascript) 
	- BDD는 함수 단위 테스트를 권장하지 않고 시나리오를 기반으로 테스트 케이스를 작성합니다. 이 시나리오는 개발자가 아닌 사람이 봐도 이해할 수 있을 정도의 수준입니다.
	- 마이크로프레임워크 : 작은 웹애플리케이션 프레임워크, 기업용 풀스택 프레임워크에 대비되는 개념
		- PHP 마이크로프레임워크
			- Bulletphp
			- Slim
			- Silex
		- Python 마이크로프레임워크
			- Flask
		- Ruby 마이크로프레임워크
			- Camping
			- Grape
			- Sinatra
		- Scala용
			- Scalatra

- `Node.js`
	- Package Manager
		- `npm` : Node Package Manager,  자바스크립트 프로그래밍 언어를 위한 **패키지 관리자** 이다.
		- `Yarn` : 하둡, **자바스크립트 패키지 매니저**, npm의 핵심 이슈(보안성? 안정성?)을 해결하기위해 나옴
	- Framework
		- `Express` : `Express.js` , 또는 간단히 `익스프레스(Express)`는 Node.js를 위한 웹 프레임워크의 하나로, MIT 허가서로 라이선스되는 자유-오픈 소스 소프트웨어로 출시되었다. 웹 애플리케이션, API 개발을 위해 설계되었다.[1] Node.js의 사실상의 **표준 서버 프레임워크** 로 불리고 있다
		- `hapi` : Hapi는 *크고 복잡한 어플리케이션에 특성화* 되어 있다. 보일러플레이트로 작성해야 할 코드가 많아서 작은 웹앱에서는 쓰기 불편하고, 예제 및 hapi로 작성된 오픈소스 앱도 적다. 이 프레임워크를 선택하면 개발자가 직접 작성해야 할 부분이 더 많을 것이다
		- `Koa` : 메모리를 덜먹고 표현력이 좋다. 다른 프레임워크에 비해 미들웨어 작성이 쉽다. 기본적으로 뼈대 프레임워크라서 제공되는 미들웨어와 함께 사용해야만 하는 Express와 Hapi와 달리, 개발자가 필요한 미들웨어만 구성해 사용할 수 있다. ES6를 도입하고 있어 ES6 제너레이터를 사용할 수 있다.
		- `Sails.js` : Node.js 환경에서 개발 된 MVC ( Model-View-Controller ) 웹 응용 프로그램 프레임 워크 이며 MIT 라이센스에 따라 무료 및 오픈 소스 소프트웨어 로 출시 된 맞춤형 엔터프라이즈 급 Node.js 웹 응용 프로그램 및 API를 쉽게 만들 수 있도록 설계되었습니다
		
	- Testing
		- `Jest` : 페이스북에 만든 테스트 프레임워크이다. 빠르게 설치하고, 테스트하기에는 좋은 것 같음
		- `Mocha` : 모카는 브라우저 지원, 비동기 테스트, 테스트 커버리지 보고서 및 모든 어설 션 라이브러리의 사용을 특징으로하는 Node.js 프로그램 용 JavaScript 테스트 프레임 워크
		- `Jasmine` : JavaScript 용 오픈 소스 테스트 프레임 워크입니다. 자바 스크립트 기반 플랫폼에서 실행되고, 애플리케이션이나 IDE에 침투하지 않으며, 읽기 쉬운 구문을 사용
		- `Chai` : Assertion Library, 
			- assert : 기본적으로 node에서 제공하는 Assert라이브러리와 유사합니다.
			- expect : BDD 스타일로 제공되는 인터페이스 중 하나로 공식 문서에서는 natural longuage처럼 chaining을 제공하여 코드를 작성할 수 있게 해준다고 합니다. 잠시 후 예제 코드로 살펴보겠습니다.
			- should : BDD 스타일로 제공되는 인터페이스 중 나머지 하나로 expect 인터페이스와 마찬가지로 chainging을 통한 API를 제공합니다.
		- `Should.js` : node.js에서 사용할 수 있는 표현적이고 가독성있으며 **테스트 프레임워크에 의존적이지 않은 단언문(assertion) 라이브러리** 입니다. 객체의 행동을 enumerable않은 단일 getter를 통해 Object를 prototype 확장해서 제공하고 있습니다.


- `Php7`
	- Package Manager
		- `Composer` :  PHP 소프트웨어와 필요 라이브러리의 의존성을 관리하기 위한 표준 포맷을 제공하는 PHP 프로그래밍 언어의 **패키지 관리자**
	- Framework
		- `Laravel` : **자유, 오픈 소스 PHP 웹 프레임워크의 하나**로, 테일러 오트웰이 개발하였으며 모델-뷰-컨트롤러 아키텍처 패턴을 따라 웹 애플리케이션을 개발하기 위해 고안됨
		- `Symfony` :  **PHP 웹 프레임워크의 하나** 로서 재사용 가능한 PHP 구성 요소/라이브러리들의 모임이다. 심포니는 2005년 10월 18일 자유 소프트웨어로 출시되었으며 MIT 허가서에 의거하여 출시됨.
			`Slim` : 간단하면서도 강력한 웹 응용 프로그램 및 API를 빠르게 작성할 수있는 **PHP 마이크로 프레임 워크**
			`Lumen` : Laravel에서 발표한 경량 프레임워크, symfony2 기반인 silex보다 1.9배 빠르다고 하는데 문법적으로는 Silm과 상당히 유사한 느낌도 듬.
			`Silex` : **PHP 마이크로프레임워크** , Symfony + Twig(템플릿 엔진) + 독트린(DB추상화) 컴포넌트 기반, PHP 버전 5.3.9 이상 필요, MIT 라이선스
	- Testing
		- `PhpUnit` : PHP 언어용 **단위테스트 프레임워크**, 첫 릴리즈: 2004년
		- `Phpspec` : PHP 언어에 작은 "specs"를 작성하여 응용 프로그램 의 내부 동작 을 설명하는 데 도움
		- `Codeception` : 테스트 도구, 부호단위 테스트, 코드 기능 테스트, 교약 수용 테스트 지원
			`Mockery` : PHPUnit, PHPSpec 또는 다른 테스트 프레임 워크를 이용한 단위 테스트에 사용되는 간단하면서도 유연한 PHP mock **객체 프레임 워크**
	- Debugger / Profiler
		- `xDebug` : 디버깅 및 프로파일 링 기능을 제공하는 **PHP 확장 모듈** 입니다. DBGp 디버깅 프로토콜을 사용
		- `XHProf` : **경량의 계층 적 및 계측 기반 프로파일러** 입니다. 데이터 수집 단계에서 프로그램의 동적 콜 그래프에서 호의 개수와 포괄적 인 메트릭을 추적
		- `New Relic` : 실시간으로 웹 및 모바일 애플리케이션을 모니터링 사용자 정의에 대한 지원 - 임의의 데이터를 수집하는 플러그인
		- `Blackfire` : 성능 관리 솔루션 . Blackfire는 개발, 테스트, 스테이징 및 프로덕션 중 애플리케이션의 수명주기 중 어느 단계에서나 성능을 프로파일 링, 테스트, 디버그 및 최적화 가능
	
- `C#` : 마이크로소프트에서 개발한 객체 지향 프로그래밍 언어,  C++와 자바의 문법과 비슷한 문법
	- `.Net` : 개발한 윈도우 프로그램 개발 및 실행 환경이다. 네트워크 작업, 인터페이스 등의 많은 작업을 캡슐화하였고, 공통 언어 런타임(Common Language Runtime)(CLR)이라는 이름의 가상 머신 위에서 작동
- `Java` :  썬 마이크로시스템즈의 제임스 고슬링(James Gosling)과 다른 연구원들이 개발한 객체 지향적 프로그래밍 언어
	- `Gradle` :  **Groovy**를 이용한 빌드 자동화 시스템이다. Groovy와 유사한 도메인 언어를 채용하였으며, 현재 안드로이드 앱을 만드는데 필요한 **안드로이드 스튜디오의 공식 빌드 시스템**
	- `Spring` : 자바 플랫폼을 위한 **오픈소스 애플리케이션 프레임워크**로서 간단히 스프링(Spring)이라고도 불린다. *동적인 웹 사이트를 개발하기 위한 여러 가지 서비스를 제공* 하고 있다. 대한민국 공공기관의 웹 서비스 개발 시 사용을 권장하고 있는 *전자정부 표준프레임워크의 기반* 기술로서 쓰이고 
	- `Play` : **모델-뷰-컨트롤러(MVC) 아키텍처 패턴**을 준수하는 오픈 소스 웹 **프레임워크**이다. 스칼라로 작성되었으며 JVM 바이트코드(예: 자바)로 컴파일된 다른 프로그래밍 언어로부터 사용 가능
- `Go` 2009년 구글이 개발한 프로그래밍 언어이다. 가비지 컬렉션 기능이 있고, 병행성(concurrent)을 잘 지원하는 컴파일 언어다.


- `Web Server`
	- `Caddy` : Caddy 웹 서버로 명확 해지며, Go로 작성된 대부분 공개 소스 인 HTTP/2 지원 **웹 서버** 입니다. HTTP 기능을 위해 Go 표준 라이브러리를 사용합니다. Caddy의 가장 주목할만한 기능 중 하나는 기본적으로 HTTPS를 활성화하는 것
	- `Apache` : 아파치 **HTTP** 서버(영어: Apache HTTP Server)는 아파치 소프트웨어 재단에서 관리하는 **HTTP 웹 서버**이다. BSD, 리눅스 등 유닉스 계열 뿐 아니라 마이크로소프트 윈도우나 노벨 넷웨어 같은 기종에서도 운용할 수 있다.
	- `Nginx` : Nginx는 **웹 서버 소프트웨어** 로, 가벼움과 높은 성능을 목표로 한다. 웹 서버, 리버스 프록시 및 메일 프록시 기능을 가짐.
- `RESTful APIs` : REST 기반으로 서비스 API를 구현한 것, 최근 OpenAPI(누구나 사용할 수 있도록 공개된 API: 구글 맵, 공공 데이터 등), 마이크로 서비스(하나의 큰 애플리케이션을 여러 개의 작은 애플리케이션으로 쪼개어 변경과 조합이 가능하도록 만든 아키텍처) 등을 제공하는 업체 대부분은 REST API를 제공한다.
- `Read about MVC`
- `Authentication`
	- `JSON Web Token(JWT)` :  웹표준 (RFC 7519) 으로서 두 개체에서 JSON 객체를 사용하여 가볍고 자가수용적인 (self-contained) 방식으로 정보를 안전성 있게 전달해줍니다.
	- `OAuth 2.0` : **외부 서비스(third-party application)의 인증 및 권한부여를 관리하는 범용 프레임워크** 입니다. OAuth 기반 서비스의 API를 호출을 할 때에는, HTTP 헤더에 `access token`을 포함하여 요청을 보내게 됩니다. 서비스는 `access token`을 검사하면서 이 요청이 유효한지 판단하여 적절한 결과를 응답
- `SOLID`
	|한글|영어|설명|
	|:---:|:---:|:---:|
	|단일 책임 | Single responsibility | 하나의 클래스는 하나의 역할을 담당하도록 함|
	|개방 폐쇄 원칙 | Open/closed principle | 확장에는 개방적, 수정에는 폐쇄적|
	|리스코프 교체 | Liskov substitution | 객체는 subtype에 관계없이 대체 가능해야 함|
	|인터페이스 분리 | Interface segregation | 다목적 인터페이스 1개보다 상황에 맞는 |다양한 인터페이스 권장|
	|의존성 역전 | Dependency inversion | 상위 모듈이 하위 모듈에 의존하면 안됨 |
- `YAGNI` : ***You aren't gonna need it : 그건 필요하지 않을거다***  
	> - 당장 필요하지 않은 것은 미리 구현하지 말자
	> - 실제로 코드가 필요하기 전까지는 해당 코드를 작성하지 말자
	> - "기능이 실제로 필요하기 전까지는 추가하지 않는 것이 좋다"라는 익스트림 프로그래밍 원칙
	> - 나중에 쓰일 것 같다는 예측에 따라 만든 것은 실제로는 10% 정도 밖에 쓰이지 않음
	> - 필요 이상의 기능을 추가하면 설계가 복잡해짐
	> - 인력은 한정적이므로 현실적 문제에 집중해야 함
	> - 코드를 빨리 구현하려면 코드를 적게 써라. 오류를 줄이려면 코드를 적게 써라.
 - `KISS`  
	 ***“Keep it small and simple.”***  
	 ***“Keep it short and simple.”***  
	 ***“Keep it simple, stupid.”***  
	 위 문장의 첫글자만 따서 만든 약어로, KISS 원칙이란 디자인에서 간단하고 알기 쉽게 만드는 편이 좋다는 원리를 말한다. 1960년에 미국 해군이 고안한 디자인 원리.
 
 
  `etc`
- `Security` : 보안...
- `GraphQL` :  **페이스북** 이 2012년에 개발하여 2015년에 공개적으로 발표된 **데이터 질의어** 이다. 그래프QL은 REST 및 부속 웹서비스 아키텍쳐를 대체할 수 있다. 클라이언트는 필요한 데이터의 구조를 지정할 수 있으며, 서버는 정확히 동일한 구조로 데이터를 반환한다. 그래프QL은 사용자가 어떤 데이터가 필요한 지 명시할 수 있게 해 주는 강타입 언어
- `Docker` 리눅스의 응용 프로그램들을 소프트웨어 컨테이너 안에 배치시키는 일을 자동화하는 오픈 소스 프로젝트


- Storage
	- Caching
		- `Memcached`  
			> - 메모리 객체 캐싱 시스템  
			> - 범용 분산형 메모리 캐시 시스템
			> - 주요용도: 데이터와 객체를 메모리에 캐시하여 DB사용을 줄여 웹사이트 속도를 빠르게 함
			> - "애플리케이션 -- memcached(고속) -- DB(저속)" 순으로 배치
			> - 신규 데이터 들어오면 예전 데이터를 사용빈도 낮은 것부터 삭제(LRU 방식)
			> - 기본포트: 11211
		- `Redis`
			> - 오픈소스 인메모리 키-값 저장소
			> - 데이터베이스, 캐시, 메세지 브로커 등으로 사용됨
			> - 지원언어: C, Go, Java, Nodejs, Lua, PHP, Python, R, Ruby 등 다수
	- Relational Databases
		- `Oracle`
			> - 오라클에서 만든 DB[1]
			> - 관계형DBMS의 하나
		- `PostgreSQL`
			> - 객체-관계형 DBMS
			> - 오픈 소스, BSD 라이센스
			> - 주요 운영체제에서 동작 (Linux, Unix(AIX, BSD, HP-UX, SGI IRIX, Mac OS X, Solaris, Tru64) Windows)
			> - 문자, 이미지, 소리, 비디오 등을 지원함
			> - 다양한 프로그래밍 인터페이스 지원 (C, C++, Java, Perl, Python, Ruby, Tcl)
			> - 기본포트: 5432
		- `MariaDB`
			> - MariaDB는 오픈 소스의 관계형 데이터베이스 관리 시스템
			> - MySQL과 동일한 소스 코드를 기반
			> - GPL v2 라이선스를 따름
			> - 오라클 소유의 현재 불확실한 MySQL의 라이선스 상태에 반발하여 만들어짐
		- `MySQL`
			> - 세계에서 가장 많이 쓰이는 오픈 소스의 관계형 데이터베이스 관리 시스템
			> - **다중 스레드, 다중 사용자, 구조질의어** 형식의 데이터베이스 관리 시스템
			> - **오라클** 이 관리 및 지원하고 있으며, Qt처럼 이중 라이선스가 적용
		- `MSSQL`
			> - 마이크로소프트 SQL 서버(영어: Microsoft SQL Server)
			> - 마이크로소프트가 1989년 사이베이스(Sybase)를 기반으로 **개발한 관계형 데이터베이스**이다.
	- NoSQL DataBases :  단순 검색 및 추가 작업을 위한 매우 최적화된 키 값 저장 공간으로, 레이턴시와 스루풋과 관련하여 상당한 성능 이익을 내는 것이 목적
		- `Redis` : 빠른 오픈 소스 인 메모리 키 값 데이터 구조 스토어이다. Redis는 다양한 인 메모리 데이터 구조 집합을 제공하므로 다양한 사용자 정의 애플리케이션을 진짜 손쉽게 생성할 수 있다
		- `MongoDB` : 도큐먼트 지향 데이터 베이스, 기본적으로 bson데이터구조(Json과 비슷한 구조)
		- `Cassandra` : 자유-오픈 소스 분산형 NoSQL 데이터베이스 관리 시스템의 하나로, 단일 장애점 없이 고성능을 제공하면서 수많은 서버 간의 대용량의 데이터를 관리하기 위해 설계
		- `RethinkDB`
		- `Couchbase`
		
		
- `Search Engines`
	- `Slor`
	- `Sphinx`
	- `ElasticSearch`
- `GOF Design Patterns`
- `Architectural Patterns`
- `Give DDD a shot`
- `Learn different testing techniques`



</div>
</details>
