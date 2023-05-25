# datasets 폴더

프로젝트 수행 시 활용한 csv 데이터셋을 모아 놓은 폴더입니다.

---

# 1. 보험료 예측_linear_regression
## 2022.02.03 ~ 2022.02.10

독립 및 종속 변수가 선형 관계에 놓여있을 때 적합하고 다른 regression 모델과 성능을 비교하는 baseline으로 사용되는 선형 회귀 알고리즘을 데이터셋에 적용 후,
보험료 예측을 위한 작업을 수행했습니다.

---

# 2. 비지도 학습_PCA
## 2022.03.02 ~ 2022.03.09

수많은 독립 변수의 갯수를 줄이면서 가능한 그 특성을 보존해내고 기존 변수 정보를 반영하는 새로운 변수를 만드는 차원 축소 작업을 PCA를 활용해 수행했습니다.

---

# 3. 비지도 학습_k_means_clustering
## 2022.02.17 ~ 2022.02.24

데이터를 적절한 수의 그룹으로 나누고, 그룹의 특징을 살펴볼 수 있는 K-means clustering 알고리즘을 해당 작업에 활용했습니다.

---

# 4. 생존자 예측_logistic_regression
## 2022.03.16 ~ 2022.03.23

독립 및 종속 변수가 선형 관계에 놓여있을 때 적합하고 다른 분류 모델과 성능을 비교하는 baseline으로 사용되는 로지스틱 회귀 알고리즘을 데이터셋에 적용 후,
여러 정보가 실제로 승객의 생존에 어떤 영향을 미치는지 예측하기 위한 작업을 수행했습니다.

---

# 5. 스팸 메일 분류_naive_bayes
## 2022.04.01 ~ 2022.04.08

독립 변수의 종류가 매우 많고, 자연어 처리에 가장 적합한 나이브 베이즈 알고리즘을 활용해 해당 분석 및 스팸 여부 판단 작업을 수행했습니다.

---

# 6. 연봉 예측_decision_tree
## 2022.06.01 ~ 2022.06.08

트리 그래프를 통한 탁월한 시각화, 다양한 트리 모델의 baseline으로써 사용되는 의사결정나무 알고리즘을 연봉 예측 작업에 적용했습니다.

---

# 7. 와인 등급 예측_KNN
## 2022.04.15 ~ 2022.04.22

outlier 가 적은 데이터에 적합하고, 다중 분류 예측에 간편히 활용될 수 있는 KNN 알고리즘을 데이터셋에 적용 후,
와인 등급 예측 작업을 수행했습니다.

---

# 8. 이상 거래 탐지_lightGBM
## 2022.07.20 ~ 2022.07.27

리프 중심 트리 분할 방식을 사용하고, XGBoost 이후로 나온 최신 부스팅 모델인 LightGBM을 이상 거래 탐지 모델링에 적용했습니다.

---

# 9. 중고차 가격 예측_random_forest
## 2022.06.15 ~ 2022.06.22

앙상블 기법을 사용한 트리 기반 모델 중 가장 보편적인 랜덤 포레스트를 활용해 중고차 가격 예측 작업을 수행했습니다.

---

# 10. 커플 성사 여부_XGBoost
## 2022.07.02 ~ 2022.07.09

순차적으로 tree를 만들어 이전 트리로부터 더 나은 트리를 만들어내는 특징을 가지는 XGBoost를 본 작업에 적용했습니다.
