# Term_Project
Lecture_Term_Project_GIT

1. 프로젝트 개요
프로젝트 명 : LSTM을 활용한 선박 성능의 예측(Prediction of ship performance using LSTM)
연구 목적 :  조선 및 해양분야에서는 에너지 효율 및 효과적인 운항 전략이 대두되면서, 선박 성능을 예측하느ㄴ 일이 중요한 역할을 하게 되었다.
본 연구는 시계열 데이터로부터 연료소모량을 예측하기 위하여 딥 러닝 접근 법의 일종인 RNN-LSTM을 활용한다.

2. 사용한 데이터셋 : 시간 간격을 따라 측정된 (90000,12)차원의 실수 Tensor

3. 사용한 모델 : RNN-LSTM

4. 딥 러닝 라이브러리 : keras

5. 실험 및 결과 요약 : LSTM 1층 node : 10개 , LSTM 2층 node 6개, seq_length : 30 의 결과
실제 모델과 예측 결과의 회귀값 : 0.840 ,  RMSE 0.02141로 수렴하는 결과를 보임.

6.  데이터는 2017dataset_3.csv 로 불러오시면 됩니다.


