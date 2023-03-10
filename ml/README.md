### Machine Learning
- Chap01 Iris예제, k-최근접 이웃 알고리즘

- Chap02 분류&회귀, **과대적합&과소적합**, k-최근접 이웃 알고리즘
  + 분류(Clsassification)와 회귀(Regression)
    + 분류
      + 미리 정의된 가능성 있는 여러 클래스 레이블 중 하나를 예측 
      + 두 개의 클래스로 분류하는 건 이진 분류(binary classification), 셋 이상의 클래스로 분류하는 건 다중 분류(multiclass classification) 이라 함
    + 회귀
      + 연속적인 숫자(실수)를 예측
      + 분류문제와 달리 회귀문제에서는 출력값의 작은 차이는 문제가 되지 않음
  
  + 과대적합(overfitting)과 과소적합(underfitting)
    + 과대적합
      + 보유하고 있는 모든 정보를 이용해 만든 복잡한 모델은 훈련 세트에만 최적화되어 새로운 데이터에 일반화 되기 어렵다. 
      + 즉, 학습 데이터에 너무 최적화를 하다보니 실제 데이터와 차이가 많이 발생하는 모델을 만들게 되는 현상
    + 과소적합
      + 이와 반대로 모델이 너무 간단하면 데이터의 다양성을 잡아내지 못하고 정확도도 떨어짐, 이를 과소적합이라 함
  
    ![generalization](https://user-images.githubusercontent.com/114986610/209783934-a18d39bc-3129-4d88-943b-70a094306efd.png)

- Chap03 선형모델-선형회귀, Ridge, Lasso, 분류용 선형

- Chap04 결정트리

- Chap05 선형과 비선형 모델, SVM

- Chap06 비지도 학습과 데이터 전처리

- Chap07 군집
