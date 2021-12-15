# 팀명 : Dhelper (델퍼)

## Larynx_Datathon 제출본 설명자료

### 코드 설명
최종 제출한 코드는 두가지로 구성되어있습니다.

1. 데이터를 전처리하는 코드 - Pre_processing.ipynb
2. 딥러닝 학습 및 평가하는 코드 - Final_Train_Evalutation.ipynb

코드 실행방법은 jupyter notebook 환경에서 각 셀을 순서대로 실행하면 됩니다.


### 모델 학습 환경

1. tensorflow-gpu = 1.15.0
2. keras = 2.3.1


### 최종 제출 모델 weight

첨부된 압축파일에 보시면 모델_Weight라는 폴더안에 All_512_AU_Net_Softmax.h5 라는 파일로 저장해두었습니다.


### 결과 요약

1.	해부학적 구조물에 대한 분할 결과의 sensitivity
    + R-TVC: 0.977
    + L-TVC: 0.973
    + R-FVC: 0.988
    + L-FVC: 0.984
    + Subjlottis: 0.977
    + Cancer : 0.959
    + Benign Tumor: 0.925

2. FP / Case: 0.0033
