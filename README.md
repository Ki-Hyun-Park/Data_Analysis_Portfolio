# Data Analysis Portfolio - 박기현(Ki Hyun Park) 
***
# [Project 1: 미국 프로농구 경기 승리 팀 예측(Kaggle Competition)](https://github.com/Ki-Hyun-Park/Kaggle_Competition)

- Background
 <p>미국 내 모든 프로 농구팀을 팀 이름을 제외한 홈팀과 방문팀으로 설정했을때 (2000 - 2012)년 동안의 농구팀별 기록 데이터를 활용한 (2013 - 2014)년도 결과 예측</p>
 
- Summary
     <p>(1). 데이터 수집 <br/>
     - 수집대상 : NBA 경기기록 <br/>
     - 수집 출처 : Kaggle </p>
*Kaggle 보러가기: [Kaggle](https://www.kaggle.com/c/fall-2019-stats-101c)*

     <p>(2). 데이터 전처리 <br/>
     - PCR을위해 반응 변수를 모두 0 혹은 1로 바꾼다(0 = 방문팀 승리 / 1 = 홈팀 승리). <br/>
     - 상관계수 행렬을 활용해 예측 영향력이있는 변수들만 추출한다. </p>

     <p>(3). 데이터 모델링 <br/>
     - 과적합을 피하기위해 기존 훈련 데이터를 "75(훈련 데이터):25(테스트 데이터)" 비율에 나눈다. <br/>
     - Lasso, LDA, Logistic, PCR, Ridge을 사용해본 결과 Ridge가 가장낮은 RMSE 및 가장 높은 유사도를 나타냈다. </p>
 
     <p>(4). 사용한 분석 툴 및 패키지 <br/>
     - 툴 : R <br/>
     - 패키지 : glmnet, dplyr, ggplot2, MASS, pls, lubridate, data.table </p>
     
     <p>(5). 피드백 <br/>
     - 모델링 및 예측 과정 자체에 관점을 두는것보다 데이터를 완벽히 분석하고 이해하는것이 더 정확한 예측 결과물을 만들수 있다. <br/>
     - 다중공선성 문제점을 해결하는게 얼마나 예측 결과물에 큰 변화를 줄수있는지 PCR 및 Ridge를 통해 알게됐다. </p>
     
<img src="images/pred_accu.png" width="350" height="350" >
 
***

# [Project 2: Curricular Complexity Project](https://github.com/Ki-Hyun-Park/Curricular_Complexity_Project)

- Background

 <p>UCLA의 15개 전공을 대상으로 졸업까지 소요되는 수업 갯수 및 시간을 EDA에 적용한것과 “STEM 전공 vs Non-STEM 전공”의 비교분석을 시각화한 인사이트 도출</p>
 
- Summary
     <p>(1). 데이터 수집 <br/>
     - 수집대상 : UCLA (항공우주공학, 간호학, 언어 & 철학, 통계학, 정치학, 미술학, 대기과학 & 해양학, 컴퓨터공학, 세계예술문화, 경제학, 생물학, 수학, 음악, 러시어학, 디자인예술학)전공 부서 <br/>
     - 수집 방법 : 각 전공 부서 방문 / R을 통한 웹 스크래핑 <br/>
     - 수집 출처 : UCLA </p>

     <p>(2). 데이터 전처리 <br/>
     - PCR을위해 반응 변수를 모두 0 혹은 1로 바꾼다(0 = 방문팀 승리 / 1 = 홈팀 승리). <br/>
     - 상관계수 행렬을 활용해 예측 영향력이있는 변수들만 추출한다. </p>

     <p>(3). 데이터 모델링 <br/>
     - 과적합을 피하기위해 기존 훈련 데이터를 "75(훈련 데이터):25(테스트 데이터)" 비율에 나눈다. <br/>
     - Lasso, LDA, Logistic, PCR, Ridge을 사용해본 결과 Ridge가 가장낮은 RMSE 및 가장 높은 유사도를 나타냈다. </p>
 
     <p>(4). 사용한 분석 툴 및 패키지 <br/>
     - 툴 : R <br/>
     - 패키지 : glmnet, dplyr, ggplot2, MASS, pls, lubridate, data.table </p>
     
     <p>(5). 피드백 <br/>
     - 모델링 및 예측 과정 자체에 관점을 두는것보다 데이터를 정확히 분석하고 이해하는것이 더 정확한 예측 결과물을 만들수 있다는걸. <br/>
     - 다중공선성 문제점을 해결하는게 얼마나 예측 결과물에 큰 변화를 줄수있는지 PCR 및 Ridge를 통해 알게됐다. </p>

 










