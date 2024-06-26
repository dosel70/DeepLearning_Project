<div align="center">
<h2>[2024] 딥러닝 이미지 분류 - CNN 프로젝트 📊</h2>
ResNet, EfficentNet, MobileNet 등 다양한 사전훈련 모델들 , 그리고 Data Augmentation, Fine_tuning 등 다양한 기법을 사용하여, 프로젝트를 진행하였습니다.
</div>

## 목차
##  1.📌 [스포츠 이미지 (100가지) 분류 프로젝트(Click!)](https://github.com/dosel70/DeepLearning_Project/wiki/%EB%94%A5%EB%9F%AC%EB%8B%9D-%E2%80%90-100%EA%B0%80%EC%A7%80-%EC%8A%A4%ED%8F%AC%EC%B8%A0-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EB%B6%84%EB%A5%98)
  - #### 😊 프로젝트 설명 (스포츠 이미지 (100가지) 분류 프로젝트)
  - 해당 프로젝트는 저용량 데이터로 이루어져 있으며, 100가지의 스포츠 이미지가 들어있는 데이터셋으로 진행하였습니다.
    
  - 위 데이터세트에서는 실제 스포츠 선수들의 운동 모습으로 이루어진 이미지가 있습니다.
    
  - 위 스포츠 이미지 분류 프로젝트는 사전훈련 모델 중 EfficentNet50과 ResNet을 사용하여 작업을 하였습니다.
    
  - EfficentNet 사전훈려모델 훈련 결과 accuracy 성능 점수가 0.97~98 사이의 값이 나왔으며, 매우 좋은 성능을 보여주었습니다.
    
  - 해당 프로젝트에서는 따로 이미지 전처리 기능을 적용시키지 않았습니다.

  - 실제 이미지를 가지고 예측을 한 결과 대부분 100%의 정답률을 보여주었습니다.
  
##  2. 📌 [Anime vs Cartoon vs Human 이미지 분류(Click!)](https://github.com/dosel70/MachineLearning-Project/wiki/ML-Project-%E2%80%90-Manufact-Quality-Rating-Predict-(Regression%E2%80%90Non-LinearData))
  - #### 😊 프로젝트 설명 (카툰 vs 애니메이션 vs 사람 이미지 CNN 분류)
  - 해당 프로젝트는 고용량 데이터로 이루어진 데이터셋으로 이루어져 있습니다.

  - 위 데이터세트에서는 서양풍 작화(Cartoon), 동양풍 작화(Anime), 사람(Human)을 구분하는 CNN 이미지 분류 프로젝트 입니다.
  
  - 해당 프로젝트에서는 EfficentNet 사전훈련 모델로 작업하였으며, 유사도가 높았기 때문에, FineTuning(미세조정)을 실시하였습니다.
  
  - FineTuning 전 EfficentNet 사전훈련 모델의 성능 점수는 accuracy가 훈련, 검증, 테스트 데이터 모두 0.98~1.00 의 값을 보여주는 매우 좋은 성능이 나왔습니다.

  - 해당 프로젝트 에서는 매우 좋은 성능이 나온 EfficentNet 사전훈련 모델을 활용해서 Fine Tuning을 진행하였고, 이 결과 또한 성능 점수가 0.99 가량의 매우 좋은 성능이 나왔습니다.
 
  - 실제 이미지를 가지고 예측을 한 결과 대부분 100%의 정답률을 보여주었습니다.
  
##  3. 📌 [계란 이미지(깨진계란 vs 정상계란) 분류 (Logistic Regression) Click!](https://github.com/dosel70/MachineLearning-Project/wiki/ML-Project-%E2%80%90-HeartFailure-Classifier-Project)   
  - #### 😊 프로젝트 설명 (깨진 계란 vs 안깨진 계란 이진 분류 이미지 데이터세트)
  - 해당 프로젝트는 깨진계란, 안깨진 계란 두개의 타겟 클래스가 존재하는 이진 분류 데이터 입니다.
  
  - 위 데이터세트는 저용량 데이터로 이루어져있으며, 회전, 좌우반전, 확대/축소와 같은 이미지 전처리 기능을 적용시켰습니다.

  - 해당 프로젝트에서는 ResNet 사전훈련 모델을 사용하여 작업을 하였으며, 유사도가 높게 나왔기때문에, FineTuning도 진행하였습니다.

  - 기존 ResNet 사전훈련 모델로 훈련결과 훈련,검증,테스트 데이터의 성능 점수가 0.96 ~ 0.98가량의 높은 성능을 보여주었습니다.

  - FineTuning 결과 Classifier Layer를 제외한 Conv Layer 부분을 freeze 하였고, 이를 통해 훈련 속도가 기존 훈련 했을 때보다 90초가량 단축할 수 있었습니다.

  - Fine tuning 결과 또한 성능 점수가 기존 훈련했을 때와 마찬가지로 0.98 가량으로 매우 높은 성능을 보여주었습니다.

  - 실제 계란 이미지를 가지고 예측을 한 결과 대부분 100%의 정답률을 보여주었습니다.
  
---
