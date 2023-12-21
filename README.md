# ESN 및 유전 알고리즘을 활용한 주가 데이터 분석과 매매 전략: 다양한 딥러닝 모델과의 비교분석 및 성능 평가

<h3>
1.  INDEXES </h3>

- <b>TAI GA 모듈화</b><br>
  8가지 기술 지표를 최적화하고 TREND를 도출함.

- <b>TREND_GridSearch</b><br>
  TREND 시그널로 도출된 투자 수익률을 최대화하는 T, P값을 구하여 최적의 TREND 시그널 추출.

<hr>
<h3>
2.  ML </h3>

- <b>ESN 백테스팅 모듈화</b><br>
  Echo State Network(ESN)를 종목별로 최적화함.

- <b>RNN 백테스팅 모듈화</b><br>
  Recurrent Neural Network(RNN)를 종목별로 최적화함.

- <b>분류모델 백테스팅 모듈화</b><br>
  Decision Tree, Random Forest, Gradient Boosting Tree(GBT), SVM, Naive Bayes를 종목별로 최적화하여 각 종목에 대해 가장 높은 수익률을 내는 모델을 선정함.

<hr>
<h3>
3.  VISUALIZATION </h3>

- <b>상대적수익률(코스피코스닥지수)</b><br>
  19개 종목에 대한 상대적 수익률 추출

- <b>Buy_and_Hold</b><br>
  19개 종목에 대한 Buy & Hold 수익률 추출

- <b>MDD 백테스팅시각화</b><br>
  19개 종목에 대한 MDD 추출

<hr>
<h3>
4.  추출된 CSV </h3>

- <b>ESN.csv</b><br>
  19개 종목에 대한 모델의 최적 파라미터와 수익률

- <b>RNN.csv</b><br>
  19개 종목에 대한 모델의 최적 파라미터와 수익률

- <b>Classification.csv</b><br>
  19개 종목에 대한 최적 분류 모델과 해당 모델의 최적 파라미터와 수익률

- <b>MDD.csv</b><br>
  19개 종목에 대한 MDD
