# Sign-Language-Classification
- Drop-In Replacement for MNIST for Hand Gesture Recognition Tasks
- pre-trained VGG16

  # epoch 5 -> 10 늘렸을때, 성능 향상

- 주의사항 (필독)
- 제출 시, 입력값의 타입 확인 요망 (submit.csv의 열 데이터별 타입)

- id: int
- label: int
- Sign Language MNIST 데이터 셋
- Sign Language MNIST는 수화 인식 문제를 다루는 데이터 셋입니다. 이 데이터 셋은 24가지 클래스로 구성된 28x28 픽셀의 그레이스케일 손 제스처 이미지로 구성되어 있습니다. 각 클래스는 알파벳 A부터 Z까지 나타내지만, 제스처 동작이 필요한 J와 Z는 제외됩니다.

- 제공되는 1D data는 (Height, Width) 형태의 data를 1D로 펼친 것입니다.

- 제공되는 파일 설명
- train.csv: 27,455개의 데이터가 있고, 각 행은 784개의 픽셀값(0~783열)과 label(마지막 열)로 구성 (27,455 x 785)
- test.csv: 7,172개의 데이터가 있고, 각 행은 784개의 픽셀값(0~783열)으로 구성 (7,172 x 784)
- sample_submission.csv: submission 파일 예시
- 라벨 정보
- 데이터 셋의 26가지 클래스는 아래와 같습니다.
- 9=J 또는 25=Z에 대한 사례는 없지만, labels=25로 설정하시면 되겠습니다.

- 0 : A
- 1 : B
- 2 : C
- 3 : D
- 4 : E
- 5 : F
- 6 : G
- 7 : H
- 8 : I
- 9 : (J는 제외)
- 10 : K
- 11 ; L
- 12 : M
- 13 : N
- 14 : O
- 15 : P
- 16 : Q
- 17 : R
- 18 : S
- 19 : T
- 20 : U
- 21 : V
- 22 : W
- 23 : X
- 24 : Y
- 25 : (Z는 제외)
