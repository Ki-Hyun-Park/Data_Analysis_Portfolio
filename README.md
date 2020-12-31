# Data Analysis Portfolio - 박기현(Ki Hyun Park) 
***
# [Project 1: 미국 프로농구 경기 승리 팀 예측(Kaggle Competition)](https://github.com/Ki-Hyun-Park/Kaggle_Competition)

- Background
 <p>미국 내 모든 프로 농구팀을 팀 이름을 제외한 홈팀과 방문팀으로 설정했을때 (2000 - 2012)년 동안의 농구팀별 기록 데이터를 활용해 (2013 - 2014)년도 결과를 5가지 모델링 방법으로 예측했습니다.</p>
 
- Summary
     <p>(1). 데이터 수집 <br/>
     - 수집대상 : NBA <br/>
     - 수집 출처 : 미국 프로농구 팬들 / 전 Dodgers 데이터 분석가 </p>

     <p>(2). 데이터 전처리 <br/>
     - PCR을위해 반응 변수를 모두 0 혹은 1로 바꿨습니다(0 = 방문팀 승리 / 1 = 홈팀 승리). <br/>
     - 상관계수 행렬을 활용해 예측 영향력이있는 변수들만 추출했습니다. </p>

     <p>(3). 데이터 모델링 <br/>
     - 과적합을 피하기위해 기존 훈련 데이터를 "75(훈련 데이터):25(테스트 데이터)" 비율에 나눴습니다. <br/>
     - Lasso, LDA, Logistic, PCR, Ridge을 사용해본 결과 Ridge가 가장낮은 RMSE 및 가장 높은 유사도를 나타냈습니다. </p>
 
     <p>(4). 사용한 분석 툴 및 패키지 <br/>
     - 툴 : R <br/>
     - 패키지 : glmnet, dplyr, ggplot2, MASS, pls, lubridate, data.table </p>
 
