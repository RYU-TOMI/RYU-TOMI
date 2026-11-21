<sub><a href="README.md">English</a> · 한국어</sub>

# 안녕하세요, RYU-TOMI입니다

서울에서 컴퓨터공학을 전공하는 학부생입니다. **실제 기계와 실제 사용자를 상대하는 데이터 파이프라인과 도구**를 만듭니다. 포뮬러 전기차의 주행 데이터 분석 엔진을 만들고 있고, 2026년 7월부터 하루 두 번 가격을 수집하는 항공권 특가 지도를 운영하고 있습니다.

- **지금 하는 일:** 자작 포뮬러 전기차 팀 [라이트온(LightOn)](https://github.com/LightOn-LEF-27)의 DAQ(데이터 수집) 파트. 목표는 FSK E-Formula 2027
- **가려는 방향:** 차량 소프트웨어, 그중에서도 데이터와 도구 쪽
- **일하는 방식:** Claude Code로 구현합니다. 범위와 구조, 검증은 제가 맡고, AI가 틀린 사례는 기록으로 남깁니다.

## 주요 작업

| 프로젝트 | 무엇인가 | 내가 한 것 |
|---|---|---|
| [**LightOnWeb**](https://github.com/LightOn-LEF-27/LightOnWeb) | 포뮬러 전기차 주행 데이터. 로깅 장비 7종의 기록을 한 형식으로 바꾸고 장비 간 시계를 맞추는 엔진, 데이터 뷰어, 트랙용 실시간 화면. MIT | 엔진과 사이트. DAQ 파트 2명 중 커밋은 전부 본인. Python · FastAPI · React · uPlot |
| [**갈래말래 (galmal)**](https://galmal.kr) | "어디 갈까?"에 답하는 한국 출발 항공권 발견 지도. 운영 중, 하루 두 번 수집. [backend](https://github.com/RYU-TOMI/galmal-backend) · [frontend](https://github.com/RYU-TOMI/galmal-frontend) · [plan](https://github.com/RYU-TOMI/galmal-plan) | 1인. 서비스 방향, 구조, 운영 |
| [**resay**](https://github.com/likelion-demoday/be) | 녹음한 대화를 화자별로 나눠 적고 대화 습관을 분석해 주는 서비스. 창업 경진대회 팀 프로젝트 | 백엔드 3명 중 1명: 인증, 사용자, 배포, 결제와 크레딧. Spring Boot |
| [**DuckSpace**](https://github.com/418teapot-sh/DuckSpace) | 덕질 굿즈를 전시하고 교환하는 플랫폼. 🏆 멋쟁이사자처럼 대학 14기 중앙 해커톤 베스트 포텐셜상 (2026) | 백엔드 3명 중 1명: 전시, 이미지 파이프라인, 1:1 채팅. Spring Boot |
| [**resume-tree**](https://github.com/RYU-TOMI/resume-tree) | 예전 Claude Code 세션을 폴더 트리와 3D 그래프에서 찾아 다시 여는 도구. MIT | 1인 |

## 중요하게 보는 것

- **믿을 수 있는 데이터.** 두 장비의 시계 속도가 조금만 달라도 결론이 뒤집힙니다. 값을 비교하기 전에 다른 물리량으로 정렬을 한 번 더 확인합니다.
- **공개 코드에 비공개 데이터를 섞지 않기.** 공개 저장소의 테스트에는 단위와 허용 오차만 두고, 실측값은 비공개 기대값 파일에 둡니다.
- **부품 사이의 약속은 하나로.** 계산은 엔진이 하고 사이트는 보여 주기만 하며, 둘 사이에 오가는 것은 버전이 붙은 문서 하나로 정합니다.

## 기술

**주로 쓰는 것:** Python · Java / Spring Boot · TypeScript / React · MySQL · Docker · AWS · GitHub Actions
**배우는 중:** STM32 C · CAN
