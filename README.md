# The Look E-Commerce 유저 수 예측

![image](https://user-images.githubusercontent.com/71024217/218958867-2779a55a-68a1-4b57-889f-fdcc555c63d8.png)

The Look E-Commerce는 GCP BigQuery의 Analytics Hub에서 제공하는 Looker팀의 의류 쇼핑몰 사이드 demo 데이터셋입니다.

BigQuery를 이용해 일일 신규 가입 유저수를 추출하여 모델 학습에 이용하였습니다.

학습하기에 앞서 ADF-test, KPSS-test를 통해 데이터의 시계열 정상성을 검증한 후 모델을 제작하였습니다.

학습 모델은 단층 LSTM 모델이며, 1주일 단위로 학습이 진행됩니다.
