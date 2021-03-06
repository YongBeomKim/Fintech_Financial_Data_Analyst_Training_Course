### 주제
- 네이버 지식인을 통한 카드사별 고객들의 애로사항 탐색


### 주제 선정 이유
- Final Project 1 진행 중 고객들의 애로사항 내역이 궁금해짐
- 인스타그램, 블로그의 경우 광고 글이 많아 네이버 지식인을 통해 확인해보기로 함

### 기간
- 2020.02.03 ~ 2020.02.18 (2주)


### 사용 언어 및 프로그램
- Python / Jupyter Notebook, Spyder

### 가설
- 신한카드, 국민카드 : 카드종류가 많아 카드추천 질문이 많을 것
- 삼성카드, 현대카드 : 코스트코 관련 카드 발급 질문이 많을 것
- 카카오카드: 체크카드보다 신용카드 관련 질문이 많을 것



### 분석 방향
- 2019년 1년을 기간으로 설정하여 네이버 지식인에서 카드사별 검색한 결과, 작성된 글의 제목만 수집
- 수집된 제목으로 워드클라우드, 워드네트워크를 수행하여 카드사별 관심 키워드 선정
- 네이버 지식인에서 '카드사' + '관심 키워드'로 검색한 결과, 작성된 글의 제목과 본문 수집
- 수집한 본문 데이터로 워드클라우드를 수행하여 카드사별 애로사항 확인 
- 결론 도출



### 나의 역할
- Final Project 1과 다른 역할 수행
- BeautifulSoup과 Selenium을 사용하여 크롤링으로 데이터 수집
    - 카드사 별 검색 결과로 나온 네이버 지식인 제목 크롤링
    - 네이버 지식인에서 '카드사' + '관심 키워드'로 검색한 결과, 네이버 지식인의 링크 크롤링
       - 링크를 통해 제목과 본문을 한번에 가져오기 위함
    - 네이버 지식인에서 '카드사' + '관심 키워드'로 검색한 결과, 작성된 글의 제목과 본문 크롤링
- 결론 도출



### 결과
- 신한카드
  - '딥드림카드'에 관련된 질문이 많음
- 국민카드
   - '탄탄대로 카드'시리즈 내 카드 추천 문의가 많음
- 삼성카드, 현대카드
  - 코스트코 발급 관련 내용이 거의 없음
- 카카오카드
  - 신용카드 문의보다 체크카드 문의가 많음
  - 캐릭터카드 발급 문의가 많음
  


### 아쉬운 점
- 네이버 지식인에 오탈자가 많고 띄어쓰기가 제대로 되지 않아 불용어 제거 및 명사추출 과정이 완벽하지 않음
- 네이버 지식인의 경우 광고성 글은 적지만, 다수의 의견을 반영하지 못하는 한계가 있음

