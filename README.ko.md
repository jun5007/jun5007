[English](./README.md) | **한국어**

# 이석준

## 소개

순천향대학교 AI빅데이터학과에서 데이터 분석, 머신러닝, 데이터 전처리를 공부하고 있습니다. 특히 금융 데이터와 시계열 데이터 분석에 관심을 두고 있습니다.

**관심 분야:** 데이터 분석 · 머신러닝 · 시계열 분석 · 금융 데이터 분석 · 데이터 전처리 · 재현 가능한 연구

## 주요 프로젝트

| 프로젝트 | 문제 | 내 역할 / 프로젝트 유형 | 상태 / 결과 | 저장소 |
|---|---|---|---|---|
| 생성형 AI 패키지 의존성 분석 | 중심 패키지, 의존성 커뮤니티, 구조적으로 유사한 대체 후보 파악 | 팀 프로젝트 | PyPI 기반 CSV 결과와 문서를 공개했으며, 수집 및 분석 파이프라인 코드는 공개하지 않았습니다. | [한국어 문서](https://github.com/jun5007/jun5007.github.io/blob/main/projects/genai-package-dependency/README.ko.md) |
| 환율 및 산업 수익률 Walk-Forward 분석 | 환율 민감도, 동조 피처, 다음 달 산업 수익률 분석 | 담당 종목 데이터를 공통 형식으로 수집·전처리했으며, Minsung Lee와 Walk-Forward Validation을 공동 개발했습니다. **Co-author이며, 논문 원고는 Minsung Lee가 작성했습니다.** | 일부 R 구현을 공개했으며, 원본 데이터가 없어 성능 재검증이 필요합니다. | [한국어 문서](https://github.com/jun5007/exchange-rate-synchronization/blob/main/README.ko.md) |
| 뉴스·검색 트렌드와 주식시장 반응 | 시장 관심도 proxy와 다음 거래일 가격·거래량 반응 탐색 | 팀원들과 네이버 검색량 수집 및 BIGKinds 뉴스 정리에 참여했고, 최종 데이터 통합 정리와 시각화를 담당했습니다. | 문서와 환경 목록을 공개했으며, 분석 코드와 데이터는 공개하지 않았습니다. | [한국어 문서](https://github.com/jun5007/issue-stock-eda/blob/main/README.ko.md) |
| DACON ETRI 휴먼이해 챌린지 | 휴먼이해 AI 대회 제출 모델 평가 | **개인 참가** | **리더보드 단계 종료.** Public Leaderboard: **1위 / 0.50143** · Final Private Leaderboard: **118위 / 0.59183** | 전용 공개 저장소 없음 · [일정](https://www.dacon.io/competitions/official/236690/overview/schedule) · [리더보드](https://www.dacon.io/competitions/official/236690/leaderboard) |

## 대회 경험

아래 기록은 **2026-07-26**에 로그인된 DACON 참가 프로필과 각 리더보드에서 다시 확인했습니다. 진행 중인 순위는 해당 날짜의 스냅샷이며 변경될 수 있습니다.

| 대회 | 상태 | 참가 유형 | 확인된 결과 | 공식 기록 |
|---|---|---|---|---|
| DACON ETRI 휴먼이해 챌린지 | **리더보드 단계 종료** | **개인** | Public: **1위 / 0.50143** · Final Private: **118위 / 0.59183** | [일정](https://www.dacon.io/competitions/official/236690/overview/schedule) · [리더보드](https://www.dacon.io/competitions/official/236690/leaderboard) |
| 2026 성균관대학교 멀티모달 AI Bias 챌린지 | **종료** | **개인** | Public: **2위 · 1** · Final Private: **33위 / 263 · 0.85952** | [일정](https://www.dacon.io/competitions/official/236722/overview/schedule) · [리더보드](https://www.dacon.io/competitions/official/236722/leaderboard) |
| 2026 Samsung Collegiate Programming Challenge: AI 챌린지 | **1차 예선 종료, 진출 여부 미검증** | **개인** | Public 스냅샷: **215위 / 640 · 0.8686** | [일정](https://www.dacon.io/competitions/official/236730/overview/schedule) · [리더보드](https://www.dacon.io/competitions/official/236730/leaderboard) |
| 제3회 풍력발전량 예측 AI 경진대회 - BARAM 2026 | **진행 중** | **개인** | — | [일정](https://www.dacon.io/competitions/official/236727/overview/schedule) · [리더보드](https://www.dacon.io/competitions/official/236727/leaderboard) |

### ETRI에서 배운 점

Public 순위와 모델의 실제 일반화 성능은 다를 수 있다는 점을 배웠습니다. 모델 개발 전에 검증 방식과 최종 제출 기준을 정하고, 다음 대회에서는 사전에 정한 로컬 검증 기준과 실험 기록을 바탕으로 모델을 선택하겠습니다.

## 논문

- 이민성, 홍찬기, 추민주, 이석준, 우지영, “환율 민감도 기반 클러스터링과 동조지수를 이용한 산업별 월간 수익률 예측,” *한국컴퓨터정보학회 2025 하계학술대회 논문집*, 제33권 제2호, pp. 959–961, 2025.07.
  - 역할: **Co-author**
  - 관련 프로젝트: [환율 및 산업 수익률 분석 한국어 문서](https://github.com/jun5007/exchange-rate-synchronization/blob/main/README.ko.md)
  - 공식 논문 정보: [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12337990)

## 기술

| 분야 | 도구 |
|---|---|
| 프로그래밍 및 쿼리 | Python, R, SQL |
| 데이터 처리 | pandas, NumPy, tidyverse |
| 머신러닝 | scikit-learn, randomForest |
| 시각화 | Matplotlib, Seaborn |
| 분석 플랫폼 | Google Analytics |
| 분석 워크플로 | Jupyter Notebook, Excel |
| 버전 관리 | Git, GitHub |

## 자격

- **Google Analytics Certification (2026)** — Google Skillshop
  - 발급일: **2026-06-12**
  - 만료일: **2027-06-12**

## 포트폴리오 사이트

- [jun5007.github.io/ko](https://jun5007.github.io/ko/)

## 연락처

- [GitHub](https://github.com/jun5007)
