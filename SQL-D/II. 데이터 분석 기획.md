# 분석 기획 방향성 도출
어떠한 목표를 달성하기 위해, 어떠한 데이터로 어떤 방식으로 수행할지 계획을 수립 <br>
수학/통계학적 지식과 IT 기술력, 도메인에 걸친 고른 역량과 시각이 요구된다. <br>
## 분석 주제 유형
1. 분석의 대상과 방법을 아는 경우 : 최적화<br>
2. 분석의 대상만을 아는 경우 : 솔루션을 찾는다<br>
3. 분석의 방법만을 아는 경우 : 통찰을 도출 <br>
4. 다 모르는 경우 : 발견 접근법으로 대상 자체를 새롭게 도출 <br>

* 분석가의 필요역량 : 분석기술/프로그래밍, 도메인지식, 의사소통 능력 + 프로젝트관리, 리더십

## 분석 방법론
1. 폭포수 모델 : 이전단계가 완료되어야 다음 단계로 진행하는 Top Down 방식<br>
2. 나선형 모델 : 점증적으로 개발하는 방법으로, 관리 체계가 효과적이지 못할 경우 복잡도가 상승한다. <br>
3. 프로토타입 모델

### KDD (Knowledge Discovery in Databases) 분석 방법론 
#### 가. 데이터셋 선택
데이터셋 선택에 앞서 <b>분석대상의 비즈니스 도메인에 대한 이해와 프로젝트 목료를 정확</b>하게 설정한다.
#### 나. 데이터 전처리
Noise와 Outlier, Missing Value를 식별하고 제거하거나 의미있는 데이터로 수정한다.
#### 다. 데이터 변환
분석 목적에 맞는 데이터를 선택하거나 데이터의 차원을 축소한다.
#### 라. 데이터 마이닝
분석 목적에 맞는 기법을 선택하여 데이터의 패턴을 찾거나 분류 또는 예측 등의 작업을 수행한다.
#### 마. 결과 평가
데이터 마이닝의 결과에 대한 해석과 분석 목적과의 일치성을 확인한다.
<br>

### CRISP-DM (Cross Industry Standard Process for Data Mining) 분석 방법론
계층적 프로세스 모델로써 4개의 레벨로 구성되어 있다.<br>
Phase > Generic Tasks > Specialized Tasks > Process Instance<br>
폭포수 모델과 달리 단계별 간 피드백이 존재한다. <br>
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FbgGzs3%2Fbtqt0a0xEOK%2FTKRgf6YaKqL09xsvWOrkkk%2Fimg.png">
출처 : https://dbrang.tistory.com/1358 <br>

### 가. 업무이해
업무 목적 파악, 상황 파악, 목표설정, 프로젝트 계획 수립
#### 나. 데이터 이해
초기 데이터 수집, 데이터 기술 분석, 데이터 탐색, 데이터 품질 확인
#### 다. 데이터 준비
분석용 데이터셋 선택, 데이터 정제, 분석용 데이터셋 편성, 데이터 통합, 데이터 포멧팅
#### 라. 모델링
모델링 기법 선택, 모델 테스트 계획 설계, 모델 작성, 모델 평가
#### 마. 평가
분석 결과 평가, 모델링 과정 평가, 모델 적용성 평가
#### 바. 전개
전개 계획 수립, 모니터링과 유지보수 계획 수립, 프로젝트 보고서 작성, 리뷰

### 빅데이터 분석 방법론
계층적 프로세스 모델로써 3계층으로 구성된다. <br>
단계> 작업> 9 월
