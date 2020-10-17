# Project: 전기자동차 충전소 설치장소 최적화
* 목표: 이용현황과 자동차 보급현황, 교통량, 인구분포 등을 이용하여 신규충전소 최적 설치 위치를 도출해낸다.
  
<br/>

### 1. 휴리스틱 P-Median 알고리즘을 이용한 자전거주차장 최적입지선정
- 링크: koreascience.or.kr/article/JAKO201330258587513.pdf
- P-Median Algorithm
  - 최단경로 매트릭스 데이터를 고려하여 최적입지를 선정
  - 종속변수가 단수일 경우에만 적용 가능
- 휴리스틱 P-Median Algorithm
  - 종속변수가 다수일 경우에도 적용 가능


### 2. 뉴욕 푸드트럭 위치 최적화
- 링크: https://borin78.tistory.com/50
- **CARTO**
  - 지도 발행/위치 분석 서비스 제공
- GBRT Model
  - Gradient Boosted Regression Tree Model
  - For Feature Extraction
  - 변수 추가에 따른 R-Squared 변동을 확인하고 유의미한 변수를 선정


### 3. 최적화 모델을 통한 카페 위치 선정 제안
- 링크: https://www.slideshare.net/YurimKim3/ss-62761272
- LSCP 
  - Location Set Covering Problem
  - 시설 간의 최대 허용 거리를 커버할 수 있는 최소의 입지 수를 결정하는 의사결정기법
  

### 4. 교통량 데이터를 활용한 전기차 충전소 위치 최적화 방안 연구 
- 링크: http://s-space.snu.ac.kr/handle/10371/166595
- 사용된 모델
  - 집합커버 모델: 지역별로 균등한 배치가 필요할 때.
  - P-Median 모델: 사용자들이 최소이동을 통해 충전소를 찾는데에 중점을 둠
  - P-Center 모델: 설비의 수가 지역에 비해 비약적으로 적을 때.

- 교통량 데이터의 유의성
  - 집합커버모델의 경우 교통량이 큰 의미를 갖지 않지만 P-Median 모델링과 P-Center 모델링의 경우에는 교통량 데이터의 의미가 큼.
  - P-Median, P-Center 모델링의 경우 통행량이 많은 대로변과 가까운 충전소가 선정되며, 평균 주행거리 및 최대 주행거리 값에 대해 이점을 보여줌.

### 5. 
