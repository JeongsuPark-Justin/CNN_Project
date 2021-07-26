# CNN_Project (전동 킥보드 헬멧 착용여부 판단)
Artificial Neural Networks and Deep Learning

## About Subject
#### Goal of the study : 
- 최근 전동 킥보드 플랫폼이 확장되면서 많은 사람들이 이용하고 있고, 이용간 헬멧 미착용 관련 사고사례가 이슈화 되고 있다. 해당 문제를 해결하기 위해 정부에서는 교통법을 개정하였지만   지켜지지 않고 있는 것이 현실이다. 따라서 우리는 이번 연구를 통해 전동 킥보드 대여 시 헬멧 미착용자에 대한 대여를 제한하는 알고리즘을 개발하고자 한다. 
#### Data Collection Plan
- 이번 프로젝트를 위해 개인 및 지인으로부터 헬멧 착용 및 미착용 영상을 수집하여 동영상을 프레임 단위로 읽어와 저장하여 데이터를 모을 예정이다. 추가적으로, 부족한 데이터는 Googling을 통하여 수집할 계획이다. 
#### A model to be used
- 헬멧을 착용한 사진을 1로 설정하고, 헬멧을 착용하지 않은 사진을 0으로 설정하여 Classification하는 CNN model을 생성하고자 한다. Optimal한 Model을 찾기 위해 여러 번 실행을 반복해 보면서 Hyper-parameter를 찾을 계획이다.
#### The expected final product example
- CNN을 통해 학습된 모델에 input data를 넣어 헬멧착용 여부를 판단 할 수 있다. 이러한 알고리즘은 킥보드 대여시 QRcode를 촬영할 때 실행된다. 전면 카메라로 헬멧 착용 여부를 확인한 뒤 최종적으로 대여 승인을 진행 하는 프로그램에 응용될 수 있다.


