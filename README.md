# VGG16_Study
VGG16 모델을 이용하여 전이 학습을 진행함.

## Data Download 및 디렉토리 구조 변경과 Shuffle
[캐글의 dogs VS cats 데이터셋 다운로드](https://www.kaggle.com/c/dogs-vs-cats/data)

PreprocessingToData.py의 코드를 이용하여 `torchvision.datasets.ImageFolder`를 이용하기 위한 디렉토리 구조로 바꾸고 shuffle을 진행한다.