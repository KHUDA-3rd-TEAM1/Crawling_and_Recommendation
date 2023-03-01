## 구조
- extColor: 색상 추출 코드 작성 부분
- selenium_crawling: 크롤링 할 때 사용한 코드와 데이터 있음
    - data.csv: 이미지 경로, 코디 설명, 코디 제목 포함
    - image/: 이미지 폴더
    - crawling_code.ipynb: 크롤링 코드
    
# 온라인 패션 잡지 사이트 크롤링을 이용한 색조합 추천 알고리즘 개발

## 배경

옷을 잘입고 싶은 마음에 인터넷 검색을 해보면 무신사같은 인터넷 쇼핑몰에서 코디를 보고 사라는 조언을 많이 해준다. 물론 사람이 직접 많은 코디를 보면서 옷의 조합을 익혀가며 패션 감각을 기르는 것이 가장 좋은 방법이지만 그럴 시간이 없는 사람이 있을 수 있고 기계가 학습을 하여 색상만이라도 추천을 해주면 옷을 고르는데 더 효율적일 수 있다. 

## 목적

본 프로젝트의 목적은 온라인 패션 잡지 사이트(무신사)에서 크롤링한 데이터를 기반으로, 적절한 색조합을 추천하는 알고리즘을 개발하는 것이다. 이를 통해, 소비자들이 만족스러운 스타일링을 구성할 수 있도록 돕고자 한다.

## 방법

1. 온라인 패션 잡지 사이트에서 스타일링 사진, 모델의 키, 몸무게를 크롤링한다. 
2. **크롤링한 데이터에서 대표되는 두가지 색상코드**를 추출한다. (그 중 한 가지를 타겟으로 지정)  
3. 분석 결과를 바탕으로, 사용자에게 적절한 색조합을 추천한다. (입력: 키, 몸무게, 색상 → 추천 색상)

## 예상 결과

본 프로젝트를 통해, 소비자들에게 적절한 색조합을 추천하는 알고리즘을 개발할 수 있을 것으로 예상된다. 이를 통해, 소비자들의 만족도를 향상시키고, 패션 시장의 발전에 기여할 수 있을 것으로 기대된다.

## 주요 기능

### 1. 색조합 추출 및 추천 서비스



- 하나의 색을 설정 했을 때 그 색과 어울리는 여러 다른 색을 추천하고, 그 색깔의 옷을 추천해준다.
- 무늬도 학습시켜보자!
- 옷 스타일 라벨링(캐주얼, 스트릿..)
- 믹스매치 : 캐주얼-스트릿

### 2. 리뷰 → 긍부정 비율 보여주기



학습 데이터 : 리뷰 데이터 

### 3.웹 서비스



## 깃허브 관리자 : jdk829355@gmail.com
