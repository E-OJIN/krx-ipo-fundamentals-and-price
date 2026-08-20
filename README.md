# KRX IPO Fundamentals and Price Analysis
> *KRX 신규 상장주 재무제표 및 주가 상관관계 분석*


## Project Overview / 프로젝트 개요
- Analyzing the correlation between KRX IPO fundamentals (operating profit margin, debt-to-equity) and post-listing stock performance from 2021 to 2025, and detecting valuation anomalies.
- 2021 ~ 2025년 KRX 신규 상장 기업의 재무 건전성 (영업이익률, 부채비율) 과 상장일 주가 성과의 상관관계를 분석하고, 이상 (고평가, 저평가) 공모주를 탐지


## Hypothesis / 가설
- Companies with higher operating profit margins and lower debt-to-equity ratios compared to their industry average prior to listing tend to show higher stock returns relative to the IPO price. 
- 상장 직전 사업연도 영업이익률이 업종 평균 대비 높고 부채비율이 낮은 기업일수록 상장일 고가 기준 공모가 대비 수익률이 높은 경향이 있다.


## Tech Stack & Data Sources / 사용 기술 및 데이터
- **Language** : Python
- **Libraries** : pandas, requests, zipfile, io, time, scipy, matplotlib, seaborn
- **Data Sources / 데이터 출처** :
  - **KRX Data Market Place** : IPO lists between 2021-2025 신규상장종목
  - **DART API** : Financial statements 재무제표
  - **FinanceDataReader** : Stock price data 주가 데이터
