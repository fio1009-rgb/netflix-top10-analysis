# Netflix TOP10 Long-Hit Analysis

넷플릭스 TOP10 데이터를 활용해
장기 흥행 콘텐츠의 특징과 첫 주 정보 기반 예측 가능성을 분석한 프로젝트입니다.

## 분석 목표
- 영화와 TV의 TOP10 유지기간 비교
- 첫 진입 순위와 장기 흥행 관계 분석
- 첫 주 시청시간과 장기 흥행 관계 분석
- 첫 주 국가 확산과 장기 흥행 관계 분석
- 로지스틱 회귀를 이용한 장기 흥행 여부 예측

## 사용 데이터
- all-weeks-global.csv
- all-weeks-countries.csv

## 사용 기술
- Python
- Google Colab
- pandas
- matplotlib
- seaborn
- scikit-learn

## 주요 결과
- Film 평균 유지기간: 2.23주
- TV 평균 유지기간: 3.24주
- 첫 주 시청시간과 유지기간 상관계수: +0.46
- 첫 진입 순위와 유지기간 상관계수: -0.38
- 국가 확산과 유지기간 상관계수: +0.43
- 로지스틱 회귀 ROC-AUC: 0.701

## 프로젝트 파일
- netflix_long_hit_analysis.ipynb
- EDA 제출 보고서
- 모델링 보고서
- 인사이트 보고서
- 최종 발표자료

## 데이터 출처
Kaggle - Netflix Top 10 Weekly Dataset
(원자료: Netflix Top 10)
