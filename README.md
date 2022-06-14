# AI_project_vision

## Vision 관련 인공지능 프로젝트를 모아둔 레포지토리

### 1) [garbage-classification](https://github.com/aimclee/AI_project_vision/tree/master/garbage-classification)

* VGG-16 network를 transfer learning을 활용하여 분리수거를 용이하게 할 수 있는 모델을 제작
* [epoch이 30](https://github.com/aimclee/AI_project_vision/blob/master/garbage-classification/VGG_16%EC%9D%84_%ED%99%9C%EC%9A%A9%ED%95%9C_trash_%EB%B6%84%EB%A5%98.ipynb)일 때는 모델 1과 모델 2 모두 80% 정도의 validation accuracy를 기록, [epoch을 100으로 늘렸을 때](https://github.com/aimclee/AI_project_vision/blob/master/garbage-classification/VGG_16%EC%9D%84_%ED%99%9C%EC%9A%A9%ED%95%9C_trash_%EB%B6%84%EB%A5%98(epoch%3D100).ipynb)는 두 모델 모두 85%의 validation accuracy를 기록. 
