### AAE: [Adversarial Auto Encoder](https://arxiv.org/abs/1511.05644) <br>
간단 정리 : AutoEncoder의 구조와 Advarsarial 학습을 사용하여 두가지의 장점을 모두 살린 생성형 모델입니다.

### DETR: [https://arxiv.org/abs/2005.12872](https://arxiv.org/abs/2005.12872)  <br>
간단 정리 : 객체 탐지의 복잡한 파이프라인을 사용하는 대신 집합 에측이라는 새로운 관점과 트랜스포머 아키텍처를 사용한 간단한 파이프라인을 제안하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-DETR)

### Co-DETR: [https://arxiv.org/abs/2211.12860](https://arxiv.org/abs/2211.12860)  <br>
간단 정리 : DETR에서 양성 쿼리의 수가 적어 효율적인 학습을 할수 없음을 지적하며, 보조 헤드를 통해 인위적으로 양성 쿼리를 만듦으로써 보다 효율적으로 학습하는 방법을 제안하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8%EB%A6%AC%EB%B7%B0-Co-DETR-DETR-with-Collaborative-Hybrid-Assignments-Training)

### Swin-Transformer: [https://arxiv.org/abs/2103.14030](https://arxiv.org/abs/2103.14030) <br>
간단 정리 : 기존의 ViT에서는 고정된 크기의 이미지, 해상도에 따른 연산량 2차식 증가 문제 제기, 계층적 구조, window와 shifted window 기반의 self-multi-head attention 제안으로 vision task의 백본을 제안  <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-Swin-Transformer-Hierarchical-Vision-Transformer-using-Shifted-Windows)


### Segment Anything: [https://arxiv.org/abs/2304.02643](https://arxiv.org/abs/2304.02643) <br>
간단 정리 : segmentation 분야에서 Foundation 모델을 제안하였습니다. Promptable 모델을 활용, 데이터를 얻기 위한 data engine 등을 활용하여 어떠한 Prompt에 대해서도 segment를 진행하는 모델과 데이터를 제안하였습니다.  <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-SA-segment-Anythings)


### End-to-End-Learning-for-self-driving-cars : [https://arxiv.org/abs/1604.07316](https://arxiv.org/abs/1604.07316) <br>
간단 정리 : 2D 이미지 입력과 운전대의 각도 데이터만을 활용하여 CNN 아키텍처를 활용한 End-to-End 자율주행이 가능함을 입증하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-End-to-End-Learning-for-Self-Driving-cars)

<br><br><br>

# Multi Modal Learning

### Show and Tell: A Neural Image Caption Generator : [https://arxiv.org/abs/1411.4555](https://arxiv.org/abs/1411.4555) <br>
간단 정리 : RNN과 CNN을 결합하여 Image caption task에서 SOTA 모달을 달성하며 서로 다른 모달리티 결합의 가능성을 보여주었습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-Show-and-Tell-A-Neural-Image-Caption-Generator)


### Show, Attend and Tell : Neural Image caption Generation with Visual Attention : [https://arxiv.org/abs/1502.03044](https://arxiv.org/abs/1502.03044) <br>
간단 정리 : 단어 예측시 이미지의 특정 부분에 집중할 수 있도록 attention 매커니즘을 제안하였습니다. 이에 모델이 단어를 예측할때 이미지의 어딜 보고 예측하는지에 대한 인사이트를 제공하였습니다.  <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-Show-Attend-and-Tell-Neural-Image-caption-Generation-with-Visual-Attention)


### ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks : [https://arxiv.org/abs/1908.02265](https://arxiv.org/abs/1908.02265) <br>
간단 정리 : 2-stream & co-attention 아키텍처를 활용하여 각 모달리티에 최적화된 특징 추출 후 각 모달리티가 서로 참조하는 구조를 통해서 자연어-이미지의 joint represnetation 사전학습 모델을 제안합니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-ViLBERT-Pretraining-Task-Agnostic-Visiolinguistic-Representations)


### Image Segmentation Using Text and Image Prompts : [https://arxiv.org/abs/2112.10003](https://arxiv.org/abs/2112.10003) <br>
간단 정리 : CLIP의 자연어-이미지 가중치를 활용하여 decoder layer를 추가한 CLIPseg 모델을 제안하였습니다. prompt로 이미지 혹은 텍스트를 입력받아 3가지 segmantation task를 사전학습 없이 수행합니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-CLIPSeg-Image-Segmentation-Using-Text-and-Image-Prompts)



<br><br><br>



<br><br><br>

# Human Pose estimation
### DeepPose: Human Pose Estimation via Deep Neural Networks
[https://arxiv.org/abs/1312.4659](https://arxiv.org/abs/1312.4659) <br>
간단 정리 : 간단한 CNN 모델을 사용하여 사람의 관절 좌표를 예측하는데 높은 성능을 보임을 제안하였습니다. 추가로 Cascade 구조를 통해서 각 좌표를 보정하여 정확도를 향상시켰습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-DeepPose-Human-Pose-Estimation-Via-Deep-Neural-Networks)


### Stacked Hourglass Networks for Human Pose Estimation
[https://arxiv.org/abs/1603.06937](https://arxiv.org/abs/1603.06937) <br>
간단 정리 : Hourglass 형태의 다운-업 샘플링 과정을 통해서 여러 스케일의 이미지 특징을 한번에 처리하는 모듈을 제안하였고, 이러한 모듈을 여러개 쌓은 하나의 큰 모델을 제안하여 pose estimation에서 높은 성능을 달성하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/Stacked-Hourglass-Networks-for-Human-Pose-Estimation)


### Deep High-Resolution Representation Learning for Human Pose Estimation
[https://arxiv.org/abs/1902.09212](https://arxiv.org/abs/1902.09212) <br>
간단 정리 : Pose Estimation 분야는 최근 다양한 스케일과 히트맵을 통한 예측이 높은 성능을 달성하고 있었다. 그래서 본 논문은 히트맵의 성능을 위해 고해상도 정보를 유지한체, 다양한 스케일의 이미지를 병렬적으로 처리할 수 있는 HRNet 모델을 제안하며 높은 성능을 달성하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-HRNet-Deep-High-Resolution-Representation-Learning-for-Human-Pose-Estimation)


### HRFormer : High-Resolution-Transformer for Dense Prediction
[https://arxiv.org/abs/2110.09408](https://arxiv.org/abs/2110.09408) <br>
간단 정리 : HRNet의 아이디어를 그대로 사용하면서 초기에는 conv, 후반에는 ViT를 쓰를 사용하여 다양한 밴치마크에서 높은 성능을 달성하였습니다. 추가로 메모리 효율적인 ViT를 설계하기 위해서 겹치지 않는 window를 설정한 후 depth wise convolution을 사용하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-HRFormer-High-Resolution-Transformer-for-Dense-Prediction)


### Token-Pruned Pose Transformer for monocular and multi-view human pose estimation
[https://arxiv.org/abs/2209.08194](https://arxiv.org/abs/2209.08194) <br>
간단 정리 : 사람이 존재하는 픽셀을 추정하는 HTI을 사용하여 사람의 위치를 추정 후 각 관절과의 attention을 통해서 픽셀의 수를 줄여 메모리 효율을 증가시면서 더 나아가 다중뷰에도 활용하였다. <br>
[BLOG]([https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-HRFormer-High-Resolution-Transformer-for-Dense-Prediction](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-PPT-token-Pruned-Pose-Transformer-for-monocular-and-multi-view-human-pose-estimation)
<br><br><br>

# Model Merging

### Distilling the Knowledge in a Neural Network
[https://arxiv.org/abs/1503.02531](https://arxiv.org/abs/1503.02531) <br>
간단 정리 : 지식을 파라미터의 가중치가 아닌 입력에 따른 출력의 확률 분포로 정의하였습니다. 이에 높은 연산량으로 학습된 모델의 출력 확률 분포를 모방하는 작은 모델을 학습 시키면 지식이 증류됨을 제안하였습니다. <br>
[BLOG](https://velog.io/@seungminchung/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-Distilling-the-Knowledge-in-a-Neural-Network)

### On the Efficacy of Knowledge Distillation
[https://arxiv.org/abs/1910.01348](https://arxiv.org/abs/1910.01348) <br>
간단 정리 : KD와 관련된 포괄적인 실험을 진행하였고, KD방식은 만능이 아니며, Student 모델의 용량을 문제로 주장하였습니다. 그리고 Student 모델과 맞는 Teacher 모델을 찾는것 보다, Teacher 모델을 정규화 하는 Early stopping 을 적용한 ESKD를 통해서 이러한 문제를 해소할 수 있다고 주장합니다. <br>
[BLOG](https://velog.io/@seungminchung/On-the-Efficacy-of-Knowledge-Distillation)

