# main

## install WLS2

[WLS2](https://docs.microsoft.com/ko-kr/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package)

## install docker

[docker for windows](https://docs.docker.com/docker-for-windows/install/)

## begin
[docker 설치](https://github.com/deeplearningzerotoall/PyTorch/blob/master/docker_user_guide.md)

재부팅 후 
1. docker 열기 <br>
2. cmd 창 열기 <br>
docker start pt <br>
docker attach pt <br>
jupyter notebook --ip 0.0.0.0 --allow-root (cmd에서 오른쪽 마우스 : 붙여넣기 가능) <br> 
비밀번호 설정

## deep learning zero to all
[youtube 강의](https://www.youtube.com/playlist?list=PLQ28Nx3M4JrhkqBVIXg-i5_CVVoS1UzAv) <br>
[github](https://github.com/deeplearningzerotoall/PyTorch)

참고
1. [파이토치로 시작하는 딥러닝](https://wikidocs.net/book/2788)
2. [https://velog.io/@gyuho/Deeper-Look-at-GD](https://velog.io/@gyuho/Deeper-Look-at-GD)


#### Implementing Gradient Descent
[참고 링크](https://atmamani.github.io/projects/ml/gradient-descent-in-python/)

#### torch.nn vs torch.nn.functional
torch.nn : class <br>
torch.nn.functional : def
label 마다 가중치 값을 줄 때 class를 사용하면 한 번만 가중치 값을 주면 되지만 def는 매번 loss를 계산할 때 줘야함 <br>
[참고 링크](https://cvml.tistory.com/10)

#### nn.BCEWithLogitsLoss vs  nn.BCELoss
logits -> nn.BCEWithLogitsLoss : sigmoid()를 없이
logits -> sigmoid -> nn.BCELoss : sigmoid()를 받아야함
