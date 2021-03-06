이미지넷(ImageNet) 데이터셋은 MNIST, CIFAR 데이터셋과 더불어 굉장히 유명한 데이터셋이다. 일반적으로 MNIST나 CIFAR는 아이디어에 대한 검증 목적으로 사용한다. 최신 컴퓨팅 장치를 기준으로 보았을 때 데이터셋 자체가 아주 작기 때문이다.
반면에 이미지넷(ImageNet)은 대표적인 대규모(large-scale) 데이터셋이다. 전체 데이터셋에 포함된 이미지만 해도 1,000만 개가 넘는다. 
이미지넷은 WordNet 계통구조에 따라 조직화되어 있다. WordNet 데이터베이스는 유의어집합(synset)의 개념에 기초해서 결정된 영어 단어들 사이의 관계를 담은 자료 집합이다.

![image](https://user-images.githubusercontent.com/89904421/149450417-79ac4216-cd0a-41d4-b1f6-b247e94fa2ba.png)

1.	데이터셋 생성 과정
유명한 Amazon Mechanical Turk 서비스를 이용하여 일일이 사람이 분류한 데이터셋이다. 
AMT란 사람들이 직접 단어에 대한 설명을 듣고 사진에 따른 클래스를 분류한 후, 돈을 받는 형태로 운영이 되었다.
Stanford University의 Li Fei-Fei 교수를 중심으로 제작 / Google, Microsofe 기업 함께 참여함
그들은 플로리다에서 컴퓨터 비전 및 패턴 인식 (CVPR)에 2009 컨퍼런스에서 포스터로 처음으로 자신의 데이터베이스를 발표했다.


2.	 사용 용도
이 데이터셋은 ILSVRC (ImageNet Large Scale Visual Recognition Challenge)로 잘 알려진 국제 대회에서 사용되는 데이터셋으로도 유명하다. 
논문에서 가장 자주 등장하는 데이터셋은 ILSVRC 2012 데이터셋이다. 최신 논문도 대개 ILSVRC 2012를 이용해 학습/평가를 진행한다.


3.	구성
이 데이터셋은 1,000개의 클래스로 구성되며 총 백만 개가 넘는 데이터를 포함한다. 약 120만 개는 학습(training)에 쓰고, 5만개는 검증(validation)에 쓴다. 학습 데이터셋 용량은 약 138GB, 검증 데이터셋 용량은 약 6GB이다. 크기는 대체로 224x224의 크기를 가지고 있다.
학습 데이터를 확인해 보면 각 클래스당 약 1,000개가량의 사진으로 구성되어 있다.
