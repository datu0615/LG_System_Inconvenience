# LG_System_Inconvenience
![20220524_131207](https://user-images.githubusercontent.com/84311270/169980902-b319ec59-5454-470a-ba61-fe0e6806d82d.png)
데이터를 통해 사용자가 불편을 느끼는 원인 분석

## Dataset
학습 데이터 (user_id : 10000 ~ 24999, 15000명)  
train_err_data.csv : 시스템에 발생한 에러 로그  
train_quality_data.csv : 시스템 퀄리티 로그  
train_problem_data.csv : 사용자 불만 및 불만이 접수된 시간  

테스트 데이터(user_id : 30000 ~ 44998, 14999명)  
test_err_data.csv : 시스템에 발생한 에러 로그   
test_quality_data.csv : 시스템 퀄리티 로그  
sample_submission.csv : 사용자 불만 확률(0~1) (제출용)  

## Model
다양한 파생변수 생성과 AutoML인 Pycaret을 이용하여 학습을 진행.
