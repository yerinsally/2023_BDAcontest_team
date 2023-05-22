# BDA_CJTheMarket
## 모델링 고도화
### 전처리 1
- weekday2 (평일/주말 및 공휴일) 적용
- most_category, num_category 제거 : 데이터 손실이 매우 크다고 판단
- ctg0~3 추가 : 해당 카테고리의 제품 구매하면 1 아니면 0 (제품이 여러 카테고리에 해당하더라도 그대로 적용)
    - 카테고리 구매 개수는 반영 x

### 전처리2 (작업 중)
- ctg0~3 : 해당 카테고리의 제품 구매 개수도 반영

## CJTheMarket 크롤링

### crawling_cj.csv 
- 카테고리별 데이터프레임 합쳐놓은 데이터프레임 (총합)

### crawling_cj0018.csv ~ crawling_cj0010.csv 
- 카테고리 번호별 데이터프레임 (개별)

### ctgrId

밥/죽/면 : 0018
  
국/김치/김/반찬/두부 : 0019
  
만두/피자/치킨 : 0020
  
핫도그/떡볶이/간식 : 0021
  
돈까스/함박/구이 : 0022
  
스팸/닭가슴살/소시지 :  0023
  
양념/소스/가루/오일 : 0004

건강식품 : 0006

신선식품 : 0007

음료/생수/시럽 : 0005

대용량 식자재 : 0009

밀키트 : 0010
