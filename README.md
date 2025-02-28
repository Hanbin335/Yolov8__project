YOLOv8-Project
---
![image](https://github.com/user-attachments/assets/8a7c537f-29cb-41fd-ae9c-cf9f5e49d107)



프로젝트 소개
----
YOLOv8이 객체 검출뿐만 아니라 인물 검출의 가능성을 확인하기 위해 인물 사진에 레이블링을 수행하였으며, 이를 통해 인물이 잘 검출되는지를 검증하고자 진행한 프로젝트

프로젝트 전체 과정
---
![image](https://github.com/user-attachments/assets/ddef3215-633b-47e8-8730-1f718abf5004)

주요 기능
---
● 데이터 레이블링 : YOLO 형식으로 레이블링한 데이터를 손쉽게 저장할 수 있는 Labelling 도구를 사용하여 YOLOv8 모델의 학습 데이터를 레이블링

● YAML 파일 생성 : YOLO와 같은 객체 검출 모델의 훈련 및 검증 데이터셋을 설정하기 위해 YAML 형식으로 데이터셋 구성을 정의

● 모델 학습 파리미터 설정 : Epochs, patience, batch_size, optimizer 등의 파라미터 설정을 하여 모델 성능을 최적화하는데 중점

● 훈련 완료 후 모델 예측 및 결과 저장 : 학습된 모델을 사용하여 테스트 데이터셋에 대한 예측을 수행하고, 예측된 이미지를 저장

개발 환경
---
● Google Colab : 클라우드 기반 Python 개발 환경으로 , GPU를 사용한 YOLO 모델 학습에 사용

● Python : 주요 프로그래밍 언어로 사용

● Google Drive : 데이터를 저장하고 불러오는 파일 시스템으로 사용

기술 스택
---
● Python yaml 모듈 : YAML 형식으로 데이터셋의 경로와 클래스 정보를 정의하고, 이를 읽고 저장하는 작업에 사용

● Ultralytics YOLO : 객체 검출 모델을 학습하고 예측하기 위해 사용

● CUDA : 모델 학습과 예측 시 GPU를 활용하여 연산 성능을 최적화.

이미지 예측
---
![image](https://github.com/user-attachments/assets/6c1294b9-bbb8-4d84-98e2-0eab6ff1dcf9)



