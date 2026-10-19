<div align="center">
<img src="https://rishavanand.github.io/static/images/greetings.gif" align="center" style="width: 100%" />
</div>

### <div align="center">장애의 원인을 데이터로 끝까지 추적해, 재발하지 않게 만드는 백엔드 개발자 이호상입니다 👨‍💻</div>

<div align="center">

[![Blog](https://img.shields.io/badge/Blog-dpdtydz.github.io-6c63ff?style=flat-square&logo=jekyll&logoColor=white)](https://dpdtydz.github.io)

</div>

- 🏫 **아이스크림에듀 학습서비스개발팀 · Backend Engineer** (2023.08 ~)
- 🧩 월간 약 7,000명(하루 평균 약 2,500명)이 학습하는 유아 학습 플랫폼 **리틀홈런** 백엔드 — 운영 어드민 · 학습 API · 게임/영어 학습 서버까지 **WAS 4개**를 맡아 설계 · 구현 · 운영 · 배포합니다
- 🔎 원인은 코드 · 로그 · 데이터로 세 번 확인하고, 고친 뒤엔 같은 문제가 다시 생기지 않게 **구조로 막는 것**을 원칙으로 합니다
- 📝 설계 결정은 ADR 로 남기고, 삽질은 [블로그](https://dpdtydz.github.io/blog)에 기록합니다

<br/>

## 🛠️ What I've been doing

| 영역 | 한 일 |
|------|------|
| 🔐 **보안** | 테스트가 없던 서버의 인증 필터를 정책 객체로 분리하고 TDD 61건, 감사 로그로 확인하며 단계적으로 적용 · 업로드 매직바이트 검증 · SSRF / 경로 순회 차단 · 로그 개인정보 마스킹 · CDN SRI |
| 🐬 **DB** | MySQL 8.0 업그레이드 대비 4개 서비스 쿼리 전수 조사 — 에러 나는 쿼리뿐 아니라 **조용히 결과가 바뀌는 쿼리**까지 미리 수정 |
| 📊 **데이터** | 학습 통계 대시보드 — 배치 사전집계 + 백필 구조, 화면마다 달랐던 회원 기준 통일 |
| ⚙️ **안정성** | 집계 배치의 트랜잭션 안 외부 호출 **0건**, 실패를 빈 결과로 덮어쓰던 '빈 성공' 제거 · 배포 중 502 **0건** · Redis 장애 시 DB 자동 전환 |
| 🚀 **성능** | API p95 **850ms → 420ms**, N+1 **41 → 4 쿼리**, 98초 실시간 집계 → 배치 |
| 🧹 **레거시** | 콜그래프 스캐너 · 매퍼 계약 검사기를 직접 만들어 미사용 코드 **약 40,000줄** 안전 제거 |

<br/>

## 💼 Career

- **2023.08 ~ 현재 · 아이스크림에듀** 학습서비스개발팀 Backend
  - [리틀홈런](https://little.home-learn.co.kr/main/index) 운영 어드민(Spring MVC · MyBatis) · 학습 API(Spring Boot · JPA) · 게임/영어 학습 서버 2개
  - 공용 학습 서버에서 리틀홈런 전용 서버 분리, 통계 대시보드 · 학습 스케줄링 · 학습자 보상 시스템 개발
  - 서비스 오픈: [언어상자](https://v.daum.net/v/20260409083003288) · [탐험상자](https://www.kfenews.co.kr/news/articleView.html?idxno=653358) · [창의상자](https://www.eduplusnews.com/news/articleView.html?idxno=16262) · [영어놀이터](https://edu.chosun.com/m/edu_article.html?contid=2025012480127) · [똑똑수학](https://www.eduplusnews.com/news/articleView.html?idxno=16119) · [화상관리](https://edu.chosun.com/m/edu_article.html?contid=2025022680071) · [공부시간 관리](https://zdnet.co.kr/view/?no=20241224082312)
- **2022.08 ~ 2023.08 · 아이스크림키즈** IT 개발팀 Backend
  - [원앤집](https://www.youtube.com/watch?v=OYw-T9wHAvE) — 레거시 JSP/Servlet → Spring Boot + Vue.js 마이그레이션, 신규 개발 · 운영
- **이전** — [Wegloo](https://github.com/ehwlfk2/Wegloo) Android 개발 · [TDP](https://github.com/hyeyoungs/TDP) Back-End 개발 · 스파르타 코딩클럽 클라우드 엔지니어 과정 1기 수료
- **수료** — Microsoft AZ-400 (DevOps) · AI-102 (Azure AI)

<br/>

## 🧰 Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_/_Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)
![OpenFeign](https://img.shields.io/badge/OpenFeign-6DB33F?style=flat-square&logo=spring&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5_·_Mockito-25A162?style=flat-square&logo=junit5&logoColor=white)

**Data & Infra**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_·_Bash-FCC624?style=flat-square&logo=linux&logoColor=black)

**Frontend**
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/AngularJS-DD0031?style=flat-square&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

<br/>

## 🚀 Side Projects

<table>
<tr>
<td width="50%">

### 🐾 [우리발자국 (Our Footprints)](https://github.com/dpdtydz/loveLogMap)
커플을 위한 위치 기반 추억 지도 앨범 & 실시간 연동 다이어리. 사진 EXIF 위치 자동 감지, 타임라인 코멘터리, 공동 여행 플래너 기능을 제공합니다.

`React` `TypeScript` `Vite` `Tailwind CSS` `Leaflet`

</td>
<td width="50%">

### 🔮 [인연사주 (Inyeon Saju)](https://github.com/dpdtydz/Fate-Analysis)
음양오행 원리로 모임과 사람 사이의 케미스트리 및 1:1 궁합을 정밀 분석하는 웹 서비스입니다.

`React` `TypeScript` `Firebase` `Tailwind CSS`

</td>
</tr>
<tr>
<td width="50%">

### 🌌 [MIND ORACLE (마인드 오라클)](https://github.com/dpdtydz/FateExplorer)
동양 사주·자미두수와 서양 점성술, Gemini AI를 결합한 통합 운명 탐색 & 감정 리포트 플랫폼입니다.

`React 19` `TypeScript` `Gemini AI` `Firebase`

</td>
<td width="50%">

### ✨ [Word Nexus (워드 넥서스)](https://github.com/dpdtydz/wordHunter)
Gemini AI가 실시간으로 단어와 캐릭터를 생성하는 수집형 행맨 퍼즐 게임입니다. 도감 수집과 실시간 랭킹 시스템을 갖췄습니다.

`React` `Express` `Gemini AI` `Firebase`

</td>
</tr>
</table>

<br/>

## ✍️ Recent Blog Posts

- [같은 이름, 다른 숫자 — 통계 지표의 분모 정하기](https://dpdtydz.github.io/2026-10-14-metric-denominator/)
- [실패를 '빈 성공'으로 돌려주지 마라 — 집계 배치가 조용히 0을 덮어쓴 이유](https://dpdtydz.github.io/2026-10-08-empty-success-fallback/)
- [외부 CDN 스크립트에 SRI 걸기 — 해시는 직접 계산하고, CDN 이 만든 .min.js 는 피한다](https://dpdtydz.github.io/2026-10-08-cdn-sri/)
- [날짜 인덱스 없는 로그에서 하루치만 읽기 — PK 이진 탐색](https://dpdtydz.github.io/2026-10-06-pk-binary-search-daily-slice/)
- [커넥션 풀 기본값의 함정 — DBCP2 LifetimeExceededException 과 wait_timeout](https://dpdtydz.github.io/2026-10-02-dbcp2-default-lifetime/)
- [로그로 개인정보가 새는 세 갈래 — 응답 원문, printStackTrace, 조용한 더미](https://dpdtydz.github.io/2026-10-01-log-pii-masking/)
- [로그 설정이 두 벌일 때 — 사라진 WARN, 무시된 springProfile](https://dpdtydz.github.io/2026-09-15-logback-two-configs/)
- [테스트 0개 레거시 서버의 인증 필터 고치기 — 판단은 순수 객체로, 차단은 관측부터](https://dpdtydz.github.io/2026-09-15-legacy-security-gate-observe-mode/)

👉 [전체 글 보기](https://dpdtydz.github.io/blog)

<br/>

## 📈 Github Stats
<div align="center"><img src="https://github-readme-stats.vercel.app/api?username=dpdtydz&show_icons=true&count_private=true&hide_border=true" align="center" /></div>

<br/>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=dpdtydz&&style=flat-square" align="center" />
</div>
