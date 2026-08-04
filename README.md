<div align="center">

# 📚 JSP · MVC · Vue.js Study Log

<br>

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=flat-square&logo=java&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<br>

> 국비 교육 과정에서 진행한 **JSP 기초부터 Vue.js까지**의 학습 내용을  
> 매일 직접 정리한 기록입니다.  
> 단순 코드 복사가 아닌, 개념·구조·흐름을 이해하고 **다시 만들 수 있도록** 작성했습니다.

<br>

![progress](https://img.shields.io/badge/진행률-완료-brightgreen?style=flat-square)
![days](https://img.shields.io/badge/학습일수-30%20days-blue?style=flat-square)

</div>

---

## 🔁 기술 스택 흐름

```
HTML / CSS
  → JSP (All-in-one)
    → MV 구조 (JSP + Model 분리)
      → MVC (JSP + Model + Servlet Controller)
        → Spring MVC 구조 직접 구현 (Mini Spring)

JDBC → DBCP → MyBatis
Oracle DB
JavaScript → jQuery → Ajax → Vue.js → WebSocket
Ubuntu 서버 배포 → GitHub 연동
```

---

## 📖 학습 기록

| 일차 | 주제 | 링크 |
|:----:|------|:----:|
| Day 01 | HTML 기초 (문서 구조, 텍스트 태그, 멀티미디어) | [📄](./day_01.md) |
| Day 02 | HTML 입력 태그, 목록 태그, table, a 링크, jQuery 실시간 검색 | [📄](./day_02.md) |
| Day 03 | CSS 선택자, 속성, 가상 클래스 / 입력 폼 심화 / select 그룹 | [📄](./day_03.md) |
| Day 04 | CSS 박스 모델, 구조/상태/문자 선택자 심화 | [📄](./day_04.md) |
| Day 05 | CSS 속성 심화 (display, background, table 스타일, 텍스트/위치/레이아웃 개요) | [📄](./day_05.md) |
| Day 06 | CSS position, 가시 속성 심화 (display/visibility/opacity/overflow/z-index), jQuery Ajax | [📄](./day_06.md) |
| Day 07 | JSP 기초 (스크립트릿/표현식/선언문), JSTL, CSS 텍스트 속성, Servlet 입문 | [📄](./day_07.md) |
| Day 08 | JSP 내장 객체 (request/response/session), 파라미터 전달, float 레이아웃, 페이징 | [📄](./day_08.md) |
| Day 09 | JSP 내장 객체 심화 (response/session/application/out/pageContext), Cookie, 파일 다운로드, Vue+Axios | [📄](./day_09.md) |
| Day 10 | DBCP, JavaBean/DTO/VO, JSP 액션 태그 (useBean/include), Session 로그인, 웹 기술 전체 흐름 | [📄](./day_10.md) |
| Day 11 | EL / JSTL 전체, MV구조 게시판 (BoardDAO/BoardModel), 파일 업로드 | [📄](./day_11.md) |
| Day 12 | MV구조 전환 실습 (일반JSP → MV), 페이징 블록, Lombok, JDBC vs DBCP 비교 | [📄](./day_12.md) |
| Day 13 | 답글형 게시판 CRUD, GET/POST 차이, jQuery Ajax 수정, JSP 총정리, XSS 보안 | [📄](./day_13.md) |
| Day 14 | MVC 구조 (Controller Servlet + Model Interface + XML 매핑), DBCPUtil 분리, Spring 구조 이해 | [📄](./day_14.md) |
| Day 15 | JSP MVC 총정리, EL/JSTL 심화, XML 파싱(DOM/SAX), MyBatis 입문, 파일 업로드 심화 | [📄](./day_15.md) |
| Day 16 | Java 어노테이션, XML 파싱(DOM/SAX), MyBatis 심화(동적SQL/config/mapper), JSP MVC 총정리 | [📄](./day_16.md) |
| Day 17 | Spring 구조 직접 구현 (커스텀 DispatcherServlet, @Controller, @RequestMapping, ComponentScan, MyBatis SqlSession) | [📄](./day_17.md) |
| Day 18 | JavaScript 기초 (변수/자료형/연산자/제어문/반복문/배열) | [📄](./day_18.md) |
| Day 19 | JavaScript 기초(배열/JSON/함수/콜백), Axios 서버 연동, HttpURLConnection | [📄](./day_19.md) |
| Day 20 | DOM 객체 모델, 이벤트 처리 3가지(인라인/고전/리스너), 동적 태그 생성/삭제, Axios 실시간 검색 필터 | [📄](./day_20.md) |
| Day 21 | jQuery 기초(선택자/css/text/html/val/attr/append), JS 내장 객체(String/Date/BOM), 우편번호 팝업 연동 | [📄](./day_21.md) |
| Day 22 | Ajax 원리(XMLHttpRequest), jQuery $.ajax + 페이징, Vue.js 기초(v-for/mounted/data), 카카오맵 API, MyBatis 동적SQL | [📄](./day_22.md) |
| Day 23 | Ubuntu 서버 환경 구축(Java21/Tomcat11), nano 편집기, GitHub clone + 배포, Git Bash push 명령어 | [📄](./day_23.md) |
| Day 24 | MVC 총정리(Cookie 최근방문/Session 로그인/댓글등록), MyBatis selectKey, forward vs redirect, jQuery 효과(fade/slide/animate/탭/라이트박스) | [📄](./day_24.md) |
| Day 25 | MVC 프로젝트 구축 순서, Config.xml+db.properties 분리, 게시판 CRUD+파일업로드/다운로드(UploadServlet/@MultipartConfig), 근처맛집 LIKE+rownum | [📄](./day_25.md) |
| Day 26 | Ajax 단계별 화면 조립(예약시스템), jsp:include 동적 include, Calendar 달력 로직, JSTL c:choose/forTokens, data-* 속성, 마이페이지/관리자 레이아웃 분리 | [📄](./day_26.md) |
| Day 27 | Vue.js 심화(생명주기/디렉티브/컴포넌트/props/$parent), v-model 양방향, axios GET/POST, ref DOM접근, 카카오맵 Geocoder 주소→좌표, function vs 화살표함수 this | [📄](./day_27.md) |
| Day 28 | Vue.js 게시판 CRUD(목록/상세/등록/수정/삭제), ES Module import, async/await, v-model+ref 유효성검사, 토글 패턴(isOn/bShow), axios POST({},{params}) | [📄](./day_28.md) |
| Day 29 | Vue 컴포넌트 emit 패턴(props+emits+$emit), 페이징 컴포넌트 재사용, 아임포트 결제(IMP.request_pay), EL+Vue 초기값 주입(${param.no}), 공통 레이아웃 include | [📄](./day_29.md) |
| Day 30 | Vue 심화(v-once/v-cloak/v-memo), computed+watch, Vue+jQuery 혼용, WebSocket 채팅(@ServerEndpoint/OnOpen/OnMessage/OnClose), MyBatis 동적SQL(if/where/choose/foreach/set) | [📄](./day_30.md) |

---

## 💡 학습 포인트

- **매일 직접 코드를 작성**하고 주석 기반으로 개념을 정리
- 단순 암기가 아닌 **"다시 만들 수 있는가"** 를 기준으로 정리
- JSP → MV → MVC 흐름을 **직접 구현하며 원리 이해**
- Spring MVC 구조를 직접 만들어봄으로써 **프레임워크 동작 원리 체득**
- MyBatis 직접 구현 과정을 통해 Spring Boot JPA와의 차이 체감

---

<div align="center">

`Java` `JSP` `Spring MVC` `MyBatis` `Oracle` `jQuery` `Ajax` `Vue.js` `WebSocket` `Ubuntu` `Git`

</div>
