# AI-Generated Image Detection

## Project Overview

AI-Generated Image Detection은 **이미지가 실제 카메라로 촬영된 사진인지, 생성형 AI 모델에 의해 만들어진 이미지인지 판별하는 AI 프로젝트**이다.

최근 Diffusion Model과 같은 이미지 생성 기술이 발전하면서 실제 사진과 AI 생성 이미지를 육안으로 구별하기 어려워지고 있다.

본 프로젝트는 실제 이미지와 다양한 생성형 AI 모델이 제작한 이미지로 구성된 대규모 데이터셋을 활용하여, 이미지의 시각적 특징과 생성 과정에서 나타나는 패턴을 학습하고 AI 생성 여부를 판별하는 딥러닝 모델을 개발하는 것을 목표로 한다.

디지털 콘텐츠의 진위 판별, 허위 이미지 탐지, 이미지 포렌식 등의 분야에 활용할 수 있는 프로젝트이다.

## Dataset

### GenImage

실제 이미지와 여러 생성형 AI 모델이 생성한 이미지로 구성된 대규모 이미지 탐지 벤치마크 데이터셋이다.

- **Dataset:** GenImage
- **Scale:** 약 268만 장의 이미지
- **Data:** Real Images, AI-Generated Images
- **Task:** Binary Image Classification (Real / AI-Generated)
- **Publication:** NeurIPS 2023
- **Generators:** Stable Diffusion, Midjourney, BigGAN, ADM, GLIDE 등 8개 생성 모델

### Links

- [Official GitHub Repository & Dataset Download](https://github.com/GenImage-Dataset/GenImage)
- [Research Paper — arXiv](https://arxiv.org/abs/2306.08571)

## Tech Stack

- Python
- PyTorch
- Computer Vision
- Deep Learning
- Image Classification
