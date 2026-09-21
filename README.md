<!-- Header Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,24,30&height=200&section=header&text=JaeUng's%20Dev%20Space&fontSize=52&animation=fadeIn&fontAlignY=38&desc=Backend%20Engineer%20%7C%20Architecture%20%26%20Scalability&descAlignY=62&descSize=20" width="100%"/>
</div>

<br/>

### 👨‍💻 About Me
* 🚀 대규모 트래픽과 안정적인 시스템 확장을 고민하는 **백엔드 엔지니어 이재웅**입니다.
* 🧩 **MSA(Microservices Architecture)** 및 이벤트 기반 설계(EDA), 캐싱 전략(Redis)을 통한 성능 최적화에 깊은 관심을 가지고 있습니다.
* 🔍 직관적인 네이밍과 코드 품질(SonarQube), 철저한 도메인 설계를 중요하게 생각합니다.
* 🎓 **NHN Academy AIoT 3기 과정 수료** (2026.01 ~ 2026.09) — Backend & MSA 심화 트랙

<div align="left">
  <a href="mailto:rnrn4308428@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/rnrn428"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
</div>

<br/>

---

### 🛠 Tech Stacks

| Category | Stacks |
| :--- | :--- |
| **Languages** | <img src="https://img.shields.io/badge/Java%2021-007396?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> |
| **Frameworks & Libs** | <img src="https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20AI-6DB33F?style=flat-square&logo=openai&logoColor=white"/> |
| **Data & Storage** | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white"/> <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white"/> |
| **Messaging & Infra** | <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Netflix%20Eureka-E50914?style=flat-square&logo=netflix&logoColor=white"/> |
| **DevOps & Quality** | <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white"/> |

<br/>

---

### 🚀 Featured Projects

#### 1. 🍄 [Yes AI Do (EcoSphere)] - 스마트 작물/버섯 재배 자동화 MSA 플랫폼
> **NHN Academy AIoT 최종 프로젝트 (팀 프로젝트)**  
> 🔗 **Team Org:** [nhnacademy-aiot3-yes-ai-do](https://github.com/nhnacademy-aiot3-yes-ai-do) | 🔗 **My Repo:** [User_server (Auth/User 마이크로서비스)](https://github.com/rnrn428/User_server)

* **개요**: IoT 센서 시계열 데이터 수집과 AI 생육 분석(Vision + LLM)을 결합한 9개 마이크로서비스 기반 엔터프라이즈 스마트팜 플랫폼
* **아키텍처**: Spring Cloud Gateway, Eureka Service Discovery, Config Server, RabbitMQ 이벤트 브로커, Multi-DB (PostgreSQL, InfluxDB, Redis, Elasticsearch, MinIO)
* **담당 역할 및 기여 (`User_server` & `Config` & `Data_generator`)**:
  * **인증/인가 파이프라인 구축**: Google OAuth2 소셜 로그인 및 자체 JWT (Access/Refresh) 토큰 발급 및 검증 로직 구현
  * **토큰 무효화 & 세션 최적화**: Redis를 도입하여 로그아웃 및 토큰 블랙리스트를 인메모리 관리, 인증 검증 오버헤드 최소화
  * **보안 & 정책 처리**: 장기 미접속자 휴면 계정 전환 정책 및 복구 플로우, 비밀번호 안전 재설정 구현
  * **코드 품질 강화**: SonarQube 정적 코드 분석을 적용하여 기술 부채 및 취약점 개선 (Quality Gate 통과)

<br/>

#### 2. 💼 [Mini Dooray] - 마이크로서비스 기반 업무 협업 플랫폼
> **NHN 협업 도구 Dooray 클론 코딩 프로젝트**

* **개요**: 기업용 업무 협업 도구를 벤치마킹하여 프로젝트 관리, 업무 할당, 계정 관리를 독립된 서비스로 분리한 협업 플랫폼
* **기술 스택**: `Spring Boot`, `Spring Security`, `Spring Data JPA`, `Docker Compose`, `MySQL`
* **핵심 기능**:
  * 멀티 모듈 및 마이크로서비스(`Account API`, `Task API`, `Gateway`, `Front`) 분리 설계
  * Docker Compose를 활용하여 전 서비스를 단일 명령어로 로컬 컨테이너 배포 환경 구축
  * RESTful 규격에 맞춘 API 설계 및 엔드포인트 보안 제어

<br/>

#### 3. 🛒 [Java Servlet & JSP Shopping Mall](https://github.com/rnrn428/java-servlet-jsp-shoppingmall) - 순수 웹 MVC 쇼핑몰
> **프레임워크 없는 순수 Java Web Architecture 구현**

* **개요**: 스프링 프레임워크의 내부 동작 원리를 체득하기 위해 순수 Servlet & JSP로 구현한 MVC 모델 2 쇼핑몰
* **기술 스택**: `Java`, `Servlet`, `JSP`, `JSTL`, `MySQL`, `Tomcat`
* **핵심 기능**:
  * Front Controller 패턴 및 View Resolver 구조를 직접 구현하여 HTTP 요청-응답 라이프사이클 체득
  * 세션/쿠키 기반 로그인 유지, 비즈니스 유효성 검증(Validation) 서비스 레이어 설계

<br/>

#### 4. ✈️ [Spring AI Flight Assistant](https://github.com/rnrn428/spring-ai-fly-schedule-ATGG_03_033) - 공공데이터 & AI 여행 어시스턴트
> **Spring AI 기반 대화형 국내 항공 스케줄 조회 서비스**

* **기술 스택**: `Spring Boot 3`, `Spring AI`, `OpenAPI (국토교통부 항공 API)`, `LLM`
* **핵심 기능**:
  * 공공데이터 오픈 API를 연동하여 실시간 항공 운항 데이터를 추출하고, Spring AI 모델과 결합
  * 사용자 자연어 질의("내일 제주 가는 항공편 알려줘")를 인식해 최적의 항공 스케줄 및 가이드를 제공

<br/>

---

### 📊 GitHub Activity & Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rnrn428&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rnrn428&layout=compact&theme=tokyonight&hide_border=true" height="150" />
</div>

<br/>

<!-- Footer Wave -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,24,30&height=100&section=footer" width="100%"/>
</div>
