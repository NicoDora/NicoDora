### 반갑습니다.

NicoDora 입니다. 👋

<br>

## 📖 My History

| Date                    |                             Organization                             | Position   |
| ----------------------- | :------------------------------------------------------------------: | ---------- |
| 2023.05.31 ~ 2024.03.08 |     [Modern Agile (6term)](https://github.com/modern-agile-team)     | Back End   |
| 2025.01.14 ~ 2025.01.28 | [Its Your Duck!](https://github.com/bokduck-bang/its-your-duck-back) | Back End   |
| 2025.01.14 ~            |              [Honey Moa](https://github.com/honey-moa)               | Back End   |

<br>

## 🕹️ Tech stack

<a><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" height="30"/></a> <a><img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=black" height="30"/></a>

<a><img src="https://img.shields.io/badge/NestJs-E0234E?style=for-the-badge&logo=NestJs&logoColor=white" height="30"/></a> <a><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" height="30"/></a>

<a><img src="https://img.shields.io/badge/auth0-EB5424.svg?&style=for-the-badge&logo=auth0&logoColor=white" height="30"/></a> <a><img src="https://img.shields.io/badge/json%20web%20tokens-323330?style=for-the-badge&logo=json-web-tokens&logoColor=white" height="30"/></a>

<a><img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white" height="30"/></a> <a><img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" height="30"/></a> <a><img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white" height="30"/></a>

<br>

## 💻 Projects

### 허니모아 (Honey Moa) [🔗](https://github.com/honey-moa/honey-moa-server)
**블로그와 채팅을 활용해 연인과의 꿀처럼 달콤한 추억을 모으는 서비스**

Nest.js, Socket.IO, PostgreSQL, AWS, Docker, GitHub Actions, Swagger\
2025.01.14 ~ 진행중

- AWS EC2 환경에서 develop 서버를 구축하고 [GitHub Actions를 사용하여 자동화된 CI/CD 환경 구축](https://nicodora.github.io/github/2025/03/18/GitHub-Actions%EB%A1%9C-CICD-%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0.html)
- [SSL 인증서 발급 및 자동 갱신 환경 구축하여 서비스의 보안성과 개발 편의 확보](https://nicodora.github.io/aws/2025/03/07/AWS-EC2%EC%97%90%EC%84%9C-Nginx%EC%99%80-Certbot%EC%9C%BC%EB%A1%9C-Lets-encrypt-SSL-%EC%9D%B8%EC%A6%9D%EC%84%9C-%EB%B0%9C%EA%B8%89%ED%95%98%EA%B8%B0.html)
- [linter•formatter(eslint + prettier) 환경에서 biome으로 마이그레이션 하여 linting•formating 에서 9배의 성능 향상 달성](https://nicodora.tistory.com/entry/Biome-Prettier%EB%B3%B4%EB%8B%A4-35%EB%B0%B0-%EB%8D%94-%EB%B9%A0%EB%A5%B4%EB%8B%A4%EB%8A%94-Biome%EC%9D%84-%EC%8D%A8%EB%B3%B4%EC%9E%90)
- Socket.IO를 사용하여 실시간 채팅 기능 구현

<br>

### 멘보샤 (Menbosha) [🔗](https://github.com/modern-agile-team/Menbosha-back)
**교내 신입생을 위한 1대1 채팅기반 멘토•멘티 서비스**

Nest.js, MySQL, Redis, Slack, Swagger\
2023.12.01 ~ 2024.03.17

- 소셜 로그인을 도입으로 가입/로그인 절차를 3단계에서 1단계로 간소화하여 유저 접근성 및 초기 이탈률 개선
- JWT를 활용한 안전하고 빠른 인증•인가 시스템 구현
- [passport strategy를 사용하여 JWT 인증로직 간소화 및 재사용성 향상](https://github.com/modern-agile-team/Menbosha-back/pull/240)
- 서버 재시작 시 Redis의 데이터가 사라지는 상황을 해결하기 위해 RDB (snapshot) 백업방식을 적용하여 데이터 영속성 보장
- 유저의 서비스 내 기여도를 측정하고 1주일마다 인기 멘토를 선정하는 자동화 기능 구현
- [ERD](https://private-user-images.githubusercontent.com/128793959/329941828-bc3d81e5-ed45-4954-ac45-b3fa2fb5e7c7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDg1MzIyNzQsIm5iZiI6MTc0ODUzMTk3NCwicGF0aCI6Ii8xMjg3OTM5NTkvMzI5OTQxODI4LWJjM2Q4MWU1LWVkNDUtNDk1NC1hYzQ1LWIzZmEyZmI1ZTdjNy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTI5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyOVQxNTE5MzRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jZGI0ZDA3NWRlYTQ4YmU5ZGQzZGI2NTJiYTAwZmQ4YmIyM2Q1MGFmYTk4NTdiNzBkOWYwZDAyNDcwNThhNTZkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.H904J3uF-8pfrAR17QA-23azxM2-IOZt1JItRt8aKno) 설계 주도, 유저 CRUD API 구현

<br>

## 💡 Experience

### 모던애자일 6기

**애자일 방법론 기반 교내 웹 개발 동아리** (2023.06.01 ~ 2024.03.08)

- 6기 부회장 및 백엔드 팀원으로서 동아리 운영 및 프로젝트 참여
- 애자일 스프린트(2주 단위)를 통해 빠른 피드백 수용 및 팀 협업 능력 강화
- 웹 개발의 전 과정을 직접 경험하며 기획부터 배포까지의 이해도 증진 및 자기주도적 학습 능력 향상
- 2주마다 테크톡(Tech Talk)을 진행하여 학습한 기술 지식을 팀원들과 공유, 지식 전달 및 발표 역량 강화
- 기수 간 멘토멘티 활동에 참여하여 개발자 간 네트워크 형성 및 정보 공유에 기여

<br>

### IDU 꿈날개 진로동아리

**교내 자기주도 진로역량강화 활동 프로그램** (2024.10.01 ~ 2024.11.30)

- 잡코리아, 사람인 등 채용 공고 사이트 분석을 통해 희망 개발 분야의 핵심 요구 역량을 파악하고, 개인 맞춤형 학습 계획 및 역량 강화 로드맵 수립
- 작성한 이력서를 팀원들과 공유하고 상호 피드백을 주고받으며 문서 작성 능력과 커뮤니케이션 스킬 향상
- 현직 개발자 선배와의 인터뷰를 통해 현업 개발 프로세스, 직무 요구 역량, 커리어 발전 방향에 대한 실질적인 이해 심화

<br>

## ✨ Activity

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=nicodora)](https://solved.ac/nicodora/) ![mazandi profile](http://mazandi.herokuapp.com/api?handle=nicodora&theme=warm)

<!-- [![GitHub Streak](https://streak-stats.demolab.com?user=NicoDora&theme=tokyonight)](https://git.io/streak-stats) -->

<img src="https://github-readme-activity-graph.vercel.app/graph?username=NicoDora&theme=vue" width="703">

<br>

<details>
<summary>hmm...</summary>
<img src="https://i.esdrop.com/d/f/WaaaCJFBsq/ABsz8K87Qv.png" wedth="703" height="703">
  
</details>
