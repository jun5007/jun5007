# Lee Seokjun | AI & Big Data Portfolio

안녕하세요. 순천향대학교 AI빅데이터학과 3학년 이석준입니다.  
데이터를 수집하고 전처리한 뒤, 통계적 해석과 머신러닝 모델을 연결해 실제 문제를 설명하는 프로젝트에 관심이 있습니다.

## Interest

- Financial data analysis
- Time-series feature engineering
- Machine learning model evaluation
- News, search trend, and market reaction analysis
- Data visualization and EDA storytelling

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4B8BBE?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## Projects

| Period | Project | Keywords | Summary |
|---|---|---|---|
| 2025.03 - 2025.06 | [환율 민감도 기반 클러스터링과 동조지수를 이용한 산업별 월간 수익률 예측](./projects/exchange-rate-synchronization/) | Time Series, Clustering, RandomForest, Association Rules | 환율 민감도와 외국인 수급을 활용해 KOSPI 대형주를 군집화하고, 산업 간 동조지수를 추가해 월간 수익률 예측 성능을 비교했습니다. |
| 2025.09 - 2025.12 | [이슈와 주식 EDA: 개인투자자의 FOMO 행동 패턴 분석](./projects/issue-stock-eda/) | EDA, News Data, Search Trend, Event Study, K-Means | 뉴스 건수와 검색량으로 이슈강도를 만들고, 종목별 주가/거래량 반응과 이슈 민감도 군집을 분석했습니다. |

## Project Highlights

### Exchange Rate Sensitivity & Industry Synchronization

- KOSPI 시가총액 상위 50개 종목, USD/KRW 환율, 외국인 지분율 변화 데이터를 결합했습니다.
- 환율 베타와 외국인 수급 변수를 기반으로 종목군을 만들고, 산업 단위의 동조 패턴을 정량화했습니다.
- Lift 기반 산업 짝과 `mean_corr` 동조지수를 RandomForest 예측 모델에 반영했습니다.
- 일부 산업에서 동조지수 추가 후 RMSE가 개선되었고, 자동차 산업은 RMSE가 약 17.6% 감소했습니다.

### Issue & Stock EDA

- KRX 주식 데이터, 네이버 데이터랩 검색량, 빅카인즈 뉴스 건수를 결합했습니다.
- `뉴스_log + 검색_log` 방식으로 이슈강도를 정의하고, 다음 거래일 반응 변수를 생성했습니다.
- 이슈강도는 다음날 가격 방향성보다 거래량 증가와 더 뚜렷한 관련을 보였습니다.
- K-Means 기반으로 종목을 고민감형, 저민감형, 중간민감형으로 분류했습니다.

## Contact

- GitHub: [jun5007](https://github.com/jun5007)
- Email / Blog / Notion / LinkedIn: 업데이트 예정

## To Improve

이 포트폴리오는 현재 제공된 보고서와 노트북을 기반으로 만든 1차 버전입니다.  
각 프로젝트에서 본인이 맡은 세부 역할과 공개 가능한 코드/데이터 범위를 추가하면 더 완성도 높은 포트폴리오가 됩니다.
