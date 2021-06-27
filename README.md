# kubernetes-for-ARM

ARM 아키텍쳐를 사용하는 디바이스에서 사용하는 Kubernetes

RPi & Jetson NANO에서 설치

<h2>전체 시스템 구성도</h2>
<img src='https://user-images.githubusercontent.com/68526662/123538422-d16f3500-d76f-11eb-8473-1a7b05a242bf.PNG'>

Kubernetes를 통해 여러대의 Edge Device를 하나로 클러스터화하여 그 위에 KubeFlow를 통한 ML 파이프라인 구축과 예측을 하고 예측 결과를 사용자들에게 서비스하는 것을 목표로 함
<h2>Node 정보</h2> 
<img src='https://user-images.githubusercontent.com/68526662/123538939-23b15580-d772-11eb-9b2a-786493425ba0.PNG'>

<p>
  Worker-node01 ~ node04 -> Jetson Nano <br />
  Worker-node11, 12 -> Raspberry Pi 4
</p>
