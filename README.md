# 김동영 | Backend Developer

Java와 Spring Boot로 웹 서비스를 개발합니다. 현재 **DunTalk의 백엔드를 개발·운영**하며 데이터 수집과 조회 성능을 개선하고 있습니다.

## DunTalk

던전앤파이터 아이템 시세를 수집·집계하고 정보를 나누는 커뮤니티 서비스입니다.

**개인 프로젝트 · 2026.06 — 현재**<br>
백엔드 설계·구현, 배포·운영 담당 · 프런트엔드는 AI 도구를 활용해 구현

[서비스 보기](https://duntalk.kr/) · [프로젝트 코드](https://github.com/kdyddd/duntalk) · [설계·성능 개선 기록](https://github.com/kdyddd/duntalk#핵심-설계와-개선)

- 외부 API 병렬 수집과 호출량 제한 적용
- 실행 계획 분석과 통계 보관 정책으로 시세 조회 지연 개선
- 커뮤니티 N+1 개선, Google 로그인과 게임 캐릭터 소유 검증 구현

**사용 기술:** Java 17 · Spring Boot · JPA · MySQL · AWS EC2 · Nginx

<a href="https://github.com/kdyddd/duntalk/blob/develop/docs/images/duntalk-item-detail.png">
  <img src="https://raw.githubusercontent.com/kdyddd/duntalk/develop/docs/images/duntalk-item-detail.png" alt="DunTalk 아이템 시세 요약과 기간별 가격·거래량 차트" width="720">
</a>

Neople API에서 수집한 판매·경매 데이터를 집계해 기간별 가격 추이와 거래량을 제공합니다.

## 프로젝트 기록

| 프로젝트 | 소개 |
| --- | --- |
| [끼리끼리](https://github.com/SunghyunKim9744/secondProject) | 프로젝트·스터디 모집과 협업을 위한 웹 서비스 |
| [심리플리 · SLPL](https://github.com/kdyddd/SLPL) | 커스텀 심리테스트를 제작하고 참여하는 웹 서비스 · [팀 저장소](https://github.com/NewLecture-web/SLPL) |
| [DunTalk 이전 코드](https://github.com/kdyddd/duntalk-old) | Spring Boot 백엔드와 Next.js 프런트엔드로 구성한 이전 버전 |

기타 기록: [자료구조·알고리즘 스터디](https://github.com/SunghyunKim9744/Algorithm-Study)
