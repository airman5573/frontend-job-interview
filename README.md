# frontend job interview
개발 면접때 자주나오는 질문들과 그에대한 상세한 설명을 기록합니다.
대충 알고있던 개념들을 더욱 명확하게 합니다. 면접대비를 위함이지만, 본질적으로는 개념을 확실하게 익히자는 의도를 갖고있습니다.

# 분류
## javascript
- `var` vs `let` vs `const`
- Scope
  - [에어맨의 스코프 정리](https://develoger.kr/frontend/scope/)
- 실행 컨택스트
  - [[10분 테코톡] 💙 하루의 실행 컨텍스트](https://www.youtube.com/watch?v=EWfujNzSUmw&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=2)
  - [[JavaScript] Execution Context(실행 컨텍스트) 정의와 종류](https://www.youtube.com/watch?v=AbNc8_poxu4)
  - [Execution Context(실행 컨텍스트) 생성과정 (hoisting 설명 포함)](https://www.youtube.com/watch?v=SpHiBkjuwQM)
- 클로저
  - [[10분 테코톡] 🍧 엘라의 Scope & Closure](https://www.youtube.com/watch?v=PVYjfrgZhtU&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=76)
  - 실제 사용 사례
- Prototype
  - [[10분 테코톡] 💼 크리스의 Prototype](https://www.youtube.com/watch?v=RYxgNZW3wl0&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=83)
- function vs arrow function
- this
  - [[10분 테코톡] 🥦 브콜의 This](https://www.youtube.com/watch?v=7RiMu2DQrb4&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=85)
- Callback Hell 탈출
  - [에어맨의 Callback Hell 탈출기](https://develoger.kr/frontend/callback-hell-%ed%83%88%ec%b6%9c%ea%b8%b0/)
- Promise
  - [[10분 테코톡] 📖 카일의 프론트엔드의 비동기](https://www.youtube.com/watch?v=fsmekO1fQcw&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=52)
- Async/Await
- Class
  - Class는 어떻게 작동하는가
- 에러 처리
  - [[10분 테코톡] 🌼 티케의 프론트엔드에서의 에러 핸들링](https://www.youtube.com/watch?v=FXtooPhupr4&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=32)
- 모듈
- Generator
  - [[10분 테코톡] 🌙 파노의 Generator & Iterator](https://www.youtube.com/watch?v=3uuBHt_SNTA&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=25)
- call vs apply vs bind
- 접근자 프로퍼티
- new
  - `new 생성자함수()` 이후 발생하는 일은?
- attribute와 property의 차이점은?
- mutable vs immutable

## 브라우저
- 렌더링 과정
  - [Browser rendering process 1편 - Browser 구성 요소](https://www.youtube.com/watch?v=oLC_QYPmtS0)
  - [Browser rendering process 2편 - 렌더링 엔진 동작과정](https://www.youtube.com/watch?v=EBe-OHkf9w8)
  - [Browser rendering process 3편 - Browser rendering optimization](https://www.youtube.com/watch?v=G4eQziVzCTE)
  - [[10분 테코톡] 🕶 곤이의 DOM&BOM](https://www.youtube.com/watch?v=q1fQnGG1bgU&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=88)
  - [[10분 테코톡] ☕️ 체프의 브라우저 렌더링](https://www.youtube.com/watch?v=sJ14cWjrNis&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=58)
- Event Loop
  - [Event loop와 call stack 은 어떻게 작동하나?](https://www.youtube.com/watch?v=zi-IG6VHBh8)
  - [[JavaScript] callback을 활용하여 비동기 호출 순서를 제어하기](https://www.youtube.com/watch?v=R9zkJhFyLPA)
  - [[10분 테코톡] 🍗 피터의 이벤트루프](https://www.youtube.com/watch?v=wcxWlyps4Vg&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=79)
  - 이벤트 루프와 실행 컨택스트
- script의 defer/async
  - [script 태그는 어떻게 외부자원을 가져오나(async, defer)](https://www.youtube.com/watch?v=c_IGI0JjtUA)
- Page Load Events
  - [DOMContentLoaded(Load 와 차이)](https://www.youtube.com/watch?v=yIjrdQDRCuk)
  - [readyState 와 페이지 로드 이벤트](https://www.youtube.com/watch?v=CbLR_5d1dDA)
- Event Listener
  - 이벤트 버블링
    - [이벤트 버블링 (기초부터 코드로 설명)](https://www.youtube.com/watch?v=DrhFKIbijvk)
  - 이벤트 캡처링
    - [이벤트 캡쳐링](https://www.youtube.com/watch?v=JyOaAlF2epY)
    - [Event order](https://www.quirksmode.org/js/events_order.html#link4)
  - `element.onclick(doSomthing)` vs `element.addEventListener(doSomething)`
- Storage
  - [[10분 테코톡] 🦄 디토의 웹스토리지 & 쿠키](https://www.youtube.com/watch?v=-4ZsGy1LOiE&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=33)
  - `cookie` vs `sessionStorage` vs `localStorage`
- 디바운스와 쓰로틀
  - [디바운스(Debounce)와 스로틀(Throttle)](https://webclub.tistory.com/607)

## 통신
- HTTP요청과 응답 과정
  - [[10분 테코톡] 🐬히로의 웹 요청과 응답](https://www.youtube.com/watch?v=xz7e-GL2g6g&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=133)
- Connection Pool & Keep-Alive
  - [[10분 테코톡] 🍪쿠기의 Connection Pool & Keep-Alive](https://www.youtube.com/watch?v=MBgEhSUOlXo&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=158)
- 요청 응답 흐름 과정
  - [[10분 테코톡] 👨‍🏫철시의 요청 응답 흐름 과정](https://www.youtube.com/watch?v=4SaW9BbtL3k&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=161)
  - [[10분 테코톡] 🎧 삭정의 Web 요청 & 응답과정](https://www.youtube.com/watch?v=0jV7xOUcKog&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=82)
  - [브라우저에 URL을 입력하면 어떤 과정이 진행될까?](https://www.youtube.com/watch?v=ipwfEUslfQA)
- HTTP 2.0
  - [[10분 테코톡] 🙆‍♂️아이크의 HTTP 2.0](https://www.youtube.com/watch?v=uhlvXrDpM-Y&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=154)
  - [[10분 테코톡] 🧃쿨라임의 HTTP/1.1, HTTP/2, 그리고 QUIC](https://www.youtube.com/watch?v=xcrjamphIp4&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=119)
  - [[10분 테코톡] 🎃손너잘의 HTTP1.1, HTTP2, 그리고 QUIC](https://www.youtube.com/watch?v=ZgSC5K1sUYM&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=49)
- Web Polling vs Web Push
  - [[10분 테코톡] 😎유니의 Web polling vs Web push](https://www.youtube.com/watch?v=v11dxmc5a0I&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=151)
- Socket
  - [[10분 테코톡] 🧲코일의 Web Socket](https://www.youtube.com/watch?v=MPQHvwPxDUw&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=94)

## 서버
- 웹서버 vs WAS
  - [[10분 테코톡] 👩‍🦰희봉의 웹서버 vs WAS](https://www.youtube.com/watch?v=NyhbNtOq0Bc&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=168)
  - [[10분 테코톡] 🎙티거의 Web server vs WAS](https://www.youtube.com/watch?v=F_vBAbjj4Pk&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=124)
  - [[10분 테코톡] 👳‍♂️ 알리의 Web Server vs WAS](https://www.youtube.com/watch?v=mcnJcjbfjrs&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=60)
- DNS
  - [[10분 테코톡] 🧑‍💻🧑‍💻동글&라면의 DNS](https://www.youtube.com/watch?v=5rBzHoR4F2A&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=99)
- Caching
  - [[10분 테코톡] 🤔디디의 Redis](https://www.youtube.com/watch?v=Gimv7hroM8A&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=92)
  - [[10분 테코톡] 🏖 파피의 Caching(캐싱)](https://www.youtube.com/watch?v=JBFT4KyEvoY&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=42)
  - [[10분 테코톡] 📸소니의 Cache](https://www.youtube.com/watch?v=NxFJ-mJdVNQ&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=115)
  - [[10분 테코톡] 🐻큰곰의 Cache](https://www.youtube.com/watch?v=c33ojJ7kE7M&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=176)

## CS
- CPU
  - [CPU는 어떻게 작동할까?](https://www.youtube.com/watch?v=Fg00LN30Ezg)
- Process vs Thread
  - [[10분 테코톡] 👩‍💻👨‍💻 쪼밀리와 오구의 Process vs Thread](https://www.youtube.com/watch?v=DmZnOg5Ced8&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=125)
  - [[10분 테코톡] 🐳김고래 Process & Thread](https://www.youtube.com/watch?v=LLiV5Yz1AWg&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=162)
  - [[10분 테코톡] 🌷 코다의 Process vs Thread](https://www.youtube.com/watch?v=1grtWKqTn50&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=57)
- OSI 7 Layers
  - [[10분 테코톡] 🔮 히히의 OSI 7 Layer](https://www.youtube.com/watch?v=1pfTxp25MA8&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=120)
  - [[10분 테코톡] 👍 파즈의 OSI 7 Layer](https://www.youtube.com/watch?v=Fl_PSiIwtEo&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=51)
- TCP & UDP
  - [[10분 테코톡] 👨‍🏫르윈의 TCP UDP](https://www.youtube.com/watch?v=ikDVGYp5dhg&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=165)
  - [[10분 테코톡] 🔮 수리의 TCP/IP](https://www.youtube.com/watch?v=BEK354TRgZ8&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=12)
- Context Switching
  - [[10분 테코톡] 🙇‍♂️코맥의 Interrupt와 Context Switching](https://www.youtube.com/watch?v=-4HKhwlH3FQ&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=160)
- Memory
  - [[10분 테코톡] ⛄️그니의 리눅스 메모리 관리](https://www.youtube.com/watch?v=OPdjLaW0flU&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=123)
  - [[10분 테코톡] 🤷‍♂️ 현구막의 리눅스 메모리 관리](https://www.youtube.com/watch?v=qxmdX449z1U&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=54)
  - [[10분 테코톡] 🤔 조엘의 GC](https://www.youtube.com/watch?v=FMUpVA0Vvjw&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=24)
  - [[10분 테코톡] 🧚🏻 배럴의 가상 메모리](https://www.youtube.com/watch?v=5pEDL6c--_k&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=16)
  - [[JavaScript] 가비지 컬렉터란? 1편 어떻게 동작하나](https://www.youtube.com/watch?v=rLx7yfdMgHQ)
  - [[JavaScript] 가비지 컬렉터란? 2편 메모리 누수를 방지하는 팁!](https://www.youtube.com/watch?v=q7AIfvWg1EE)
- File System
  - [[10분 테코톡] 🍊오렌지의 리눅스 파일 시스템](https://www.youtube.com/watch?v=oeuVjeeoLSQ&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=121)
  - [[10분 테코톡] 🕺 루트의 리눅스 파일 시스템](https://www.youtube.com/watch?v=FiK0Hu5Pr3Q&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=53)

## React
- Composition
  - [[10분 테코톡] ⛰ 로키의 상속보다는 Composition](https://www.youtube.com/watch?v=clbpnp2xYOQ&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=81)
  - [[10분 테코톡] ☀️앨런의 상속보다는 Composition](https://www.youtube.com/watch?v=YJ4JJsGy8rY&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=134)
- VirtualDOM
  - [[10분 테코톡] 🥁 지그의 Virtual DOM](https://www.youtube.com/watch?v=PN_WmsgbQCo&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=61)
- Suspense
  - [초간단 비동기 렌더링 React Suspense](https://www.youtube.com/watch?v=8q7OQSPLF4k)
- Reconsile
  - [Lin Clark - A Cartoon Intro to Fiber - React Conf 2017](https://www.youtube.com/watch?v=ZCuYPiUIONs)
  - [Understanding React's UI Rendering Process](https://www.youtube.com/watch?v=i793Qm6kv3U)
  - [SMOOSHCAST: React Fiber Deep Dive with Dan Abramov](https://www.youtube.com/watch?v=aS41Y_eyNrU)
- 생명주기
- useMemo vs useCallback vs React.memo
- Custom Hook
- 리액트에서 클로저가 사용되는 경우
- onClick에 들어가는 handler함수가 변경될때 re-rendering되는가?
- React vs Vue vs Angular
- SPA의 단점
- Class Component vs Functional Component
- High-Order-Function

## Design Pattern
- MVC Pattern
  - [[10분 테코톡] 🐝범블비의 MVC Pattern](https://www.youtube.com/watch?v=es1ckjHOzTI&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=137)
  - [[10분 테코톡] 👩🏻‍💻👨🏻‍💻해리&션의 MVC 패턴](https://www.youtube.com/watch?v=uoVNJkyXX0I&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=179)
  - [[10분 테코톡] 🙋‍♂️제이엠의 MVC](https://www.youtube.com/watch?v=nMolWzTT-dU&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=159)
  - [[10분 테코톡] 🧀 제리의 MVC 패턴](https://www.youtube.com/watch?v=ogaXW6KPc8I&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=86)
- OOP Pattern
  - [[10분 테코톡] 🍟 웨지의 OOP](https://www.youtube.com/watch?v=3etKkkna-f0&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=75)
  - [[Javascript]OOP in javascript - 객체지향 프로그래밍에 대해 알아보자](https://www.youtube.com/watch?v=Ws_GHE5D62s)
- Singleton Pattern
  - [[10분 테코톡] 🧇 크로플의 싱글턴과 정적클래스](https://www.youtube.com/watch?v=C6CczyrkYXU&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=72)
- Event Delegation Pattern
  - [이벤트 위임의 정의와 활용](https://www.youtube.com/watch?v=8Rzf6IHq1Fw)
  - [이벤트위임 활용 2 - 행동패턴](https://www.youtube.com/watch?v=rSPHytB0vUA)

## 보안
- XSS
  - [[10분 테코톡] 🔧알트의 XSS](https://www.youtube.com/watch?v=bSGqBoZd8WM&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=102)
- HTTPS
  - [[10분 테코톡] 🍭 다니의 HTTPS](https://www.youtube.com/watch?v=wPdH7lJ8jf0&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=20)
- SOP(Same Origin Policy)
- CORS(Cross-Origin Resource Sharing)
  - [[10분 테코톡] ⚽코나스의 CORS](https://www.youtube.com/watch?v=_sLjXviYivM&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=149)
  - [[10분 테코톡] 🤠럿고의 CORS](https://www.youtube.com/watch?v=7iGIfcEsc2g&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=101)
  - [[10분 테코톡] 🌳 나봄의 CORS](https://www.youtube.com/watch?v=-2TgkKYmJt4&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=55)
  - [CORS에 영향 받지 않고 Request할 수 있는 경우](https://homoefficio.github.io/2015/07/21/Cross-Origin-Resource-Sharing/)

## 기타 등등
- 프레임워크 vs 라이브러리 vs API
  - [[10분 테코톡] 🌳임루트의 프레임워크 vs 라이브러리 vs API](https://www.youtube.com/watch?v=-ZG8uX7mpuk&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=131)
  - [[10분 테코톡] 🙆‍♀️티버의 API vs Library vs Framework](https://www.youtube.com/watch?v=We8JKbNQeLo&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=164)
  - [[10분 테코톡] 📢 욘의 프레임워크 vs 라이브러리 vs API](https://www.youtube.com/watch?v=_j4u4ftWwhQ&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=67)
- 인증
  - [[10분 테코톡] 🎡토니의 인증과 인가](https://www.youtube.com/watch?v=y0xMXlOAfss&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=118)
  - [[10분 테코톡] 🌳 나봄의 인증과 인가](https://www.youtube.com/watch?v=TXWUNePimAc&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=47)
  - JWT(JSON WEB TOKEN)
- Blocking vs Non-Blocking
  - [[10분 테코톡] 🐰 멍토의 Blocking vs Non-Blocking, Sync vs Async](https://www.youtube.com/watch?v=oEIoqGd-Sns&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=56)
- Test
  - [[10분 테코톡] 🎪 도비의 프론트엔드에서의 테스트 종류](https://www.youtube.com/watch?v=pkYUcKWOqPs&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=50)
  - [[10분 테코톡] 🍺 서니의 프론트엔드 성능 측정](https://www.youtube.com/watch?v=A6J74xLWqYg&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=37) 
- 배포
  - [[10분 테코톡] 🍟 웨지의 지속적 배포](https://www.youtube.com/watch?v=X6QGhg19Kqg&list=PLgXGHBqgT2TvpJ_p9L_yZKPifgdBOzdVH&index=29)
- HTML
  - `<img srcset="..."` `srcset` 속성의 역할은?
  - `<a>`태그 안에 `<button>`을 써도 되는가?
    - [Can I nest a <button> element inside an <a> using HTML5?](https://stackoverflow.com/a/6393863/9279003)
    - [codepen 테스트](https://codepen.io/YOONBYEONGIN/pen/eYGyYXV)
  - 왜 CSS `<link>`를 `<head>`에 놓는것이 좋은가?