# 🕸️ 웹크롤링 실습 과제

웹 데이터를 수집하고 분석하는 능력을 키우기 위한 웹크롤링 실습 과제로 각 과제는 난이도별로 구성되어 있으며, 실습 후 간단한 분석 또는 시각화 작업이 포함
---> 보고서 형태로 작성하여 PDF로 eclass에 과제 제출하시오.
---

## ✅ 과제 1: 실시간 뉴스 헤드라인 수집 (기초)

- **목표:** 네이버 뉴스에서 특정 키워드의 최신 뉴스 제목 수집 및 저장
- **주제 예시:** `인공지능`, `빅데이터`, `삼성전자` 등
- **수행 내용:**
  - 네이버 뉴스 검색 URL 구조 분석
  - BeautifulSoup 또는 Selenium을 이용하여 뉴스 제목, 날짜, 링크 수집
  - 수집된 데이터를 CSV 파일로 저장
- **추가 미션:**
  - 뉴스 제목을 기반으로 워드클라우드 시각화
- **활용 기술:** `requests`, `BeautifulSoup`, `pandas`, `matplotlib`, `wordcloud`

---

## ✅ 과제 2: 중고마켓 가격 데이터 수집 및 분석 (중급)

- **목표:** 쿠팡, 당근마켓 또는 번개장터 등에서 특정 제품(노크북)의 중고 판매 데이터 수집
- **제품 예시:** `아이폰`, `갤럭시탭`, `에어팟`
- **수행 내용:**
  - 지역 필터 및 페이징 URL 구조 분석
  - 제품명, 가격, 등록일, 상품 설명 수집
  - 수집된 데이터를 기반으로 가격 분포 시각화 (히스토그램, 박스플롯)
- **추가 미션:**
  - 평균 가격 기준 이상/이하 상품 탐지 및 필터링
- **활용 기술:** `Selenium`, `pandas`, `seaborn`, `re`

---

## ✅ 과제 3: 쇼핑몰 리뷰 수집 및 감성 분석 (고급)

- **목표:** 온라인 쇼핑몰 상품 리뷰를 수집하고 간단한 감성 분석(Sentiment Analysis) 수행
- **대상 사이트:** 쿠팡, G마켓 등
- **수행 내용:**
  - 상품명, 평점, 리뷰 내용 크롤링
  - 리뷰 수 상위 상품 3개 비교 분석
  - 긍정/부정 키워드 기반 리뷰 분류
- **추가 미션:**
  - 긍정/부정 키워드 시각화 (워드클라우드)
- **활용 기술:** `Selenium`, `pandas`, `nltk` 또는 `KoNLPy`, `wordcloud`, `Hugging face Transformer`

---
