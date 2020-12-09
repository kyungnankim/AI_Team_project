# AI Team Project

## 목표
실시간 음성을 입력을 받아 음계를 예측하고 예측한 음계에 맞는 캐릭터 움직이는 프로젝트

<br>

----------------

<br>


## preprocessing 모듈
학습시킬 데이터를 전처리 하여 npy 파일로 저장

### 전처리 과정

1. 학습 시킬 원본데이터 분석
- 학습 시킬 wav 파일을 matplolib으로 출력하니 x축은 시간 y축은 데시벨이 출력된다.
<a href='![db_graph](https://user-images.githubusercontent.com/50133267/101586871-30fd3180-3a26-11eb-9048-7150dd0c24a1.png)
'>wav의 데시벨 그래프</a>

<br>

----

<br>

## model 모듈
전처리 한 npy 파일을 이용하여 모델을 학습하여 모델을 저장

<br>

----

<br>

## live_to_scale
저장한 모듈을 사용하여 실시간 마이크 입력으로 도, 레, 미, 파, 솔, 라, 시 출력