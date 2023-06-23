# 코스피 50 종목에 대한 뉴스를 크롤링하여 감성 분석
## 개요
- 목적: 주식 종목에 대한 뉴스 데이터를 감성 분석하여 종목 선별에 참고
- 방법: 감성 사전 기반 뉴스 제목 스코어링(긍정 +1, 부정 -1)
- 기술 스택: python, beautifulsoup4, pandas, konlpy, pykrx

## 사용법
1. `get_dataset.ipynb`의 모든 셀을 성공적으로 실행하면 data 폴더에 뉴스 크롤링 데이터가 생성된다.
2. `run_analysus.ipynb`의 모든 셀을 성공적으로 실행하면 results 폴더에 3개의 결과 파일이 생성된다.
    - `best_stocks...xlsx`: 상위 종목의 뉴스 데이터
    - `worst_stocks...xlsx`: 하위 종목의 뉴스 데이터
    - `score...xlsx`: 전체 점수 순위 데이터

## 예시
- 뉴스 크롤링 데이터
<img src="/assets/news_sample.JPG" width="500"/>
- 전체 점수 순위 데이터(내림차순)
<img src="/assets/score_sample.JPG" width="400"/>