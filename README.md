# BDA_CJTheMarket

## 시현
#### 카테고리 (0/1로 반영)
- cj_empY.csv (임직원 : 설 연휴 포함)
- cj_empN.csv (비임직원 : 설 연휴 제거)
-> num_category 열은 제거하는 게 성능이 더 좋게 나옴 (현재 데이터프레임엔 일단 포함시킴)
#### 카테고리 (개수로 반영)
- cj_empY2.csv (임직원 : 설 연휴 포함)
- cj_empN2.csv (비임직원 : 설 연휴 제거)
-> 비임직원인 경우만 num_category 열은 제거하는 게 성능이 더 좋게 나옴 (현재 데이터프레임엔 일단 포함시킴)
#### ipynb
* [최종]데이터전처리_카테고리ind    -> cj_empY.csv & cj_empN.csv
  - 임직원) 다운받은 파일 상태 그대로 코드 돌리기
  - 비임직원) line 13 주석 풀고, 임직원 데이터 생성 및 저장하는 부분(line62) 주석처리, 비임직원 코드 주석 풀고 코드 돌리기

* [최종]데이터전처리_카테고리cnt    -> cj_empY2.csv & cj_empN2.csv
  - 임직원) 다운받은 파일 상태 그대로 코드 돌리기
  - 비임직원) line 13 주석 풀고, 임직원 데이터 생성 및 저장하는 부분(line50) 주석처리, 비임직원 코드 주석 풀고 코드 돌리기


## 성연
#### 가장 성능이 높게 나온 데이터셋
- cj_cate2.csv
- 데이터 전처리_가설검증_cate2.ipynb

#### cj_cate2.csv와 컬럼을 맞춘 테스트 데이터
- cj_test.csv
- test 데이터 전처리.ipynb

