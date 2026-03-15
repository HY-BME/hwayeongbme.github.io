---
title: "지도학습의 의미와 종류"
excerpt: "지도학습의 의미 및 알고리즘 종류에 대하여 학습"

categories:
  - ML
tags:
  - [tag1, tag2]

permalink: /ML/post-name-here-1/

toc: true
toc_sticky: true

date: 2026-03-15
last_modified_at: 2026-03-15
---

## 🦥 지도학습의 의미와 종류
<img width="672" height="312" alt="Image" src="https://github.com/user-attachments/assets/3a28547c-fd5e-4d7e-81f8-f0f290171327" />

&nbsp;
&nbsp;

**지도학습(Supervised Learning)**

지도 학습은 정답이 있는 데이터(labelled data)를 활용해 훈련 데이터로부터 프로그램 등을 학습시켜서 결과에 대한 예측을 만들어내는 기계 학습(Machine Learning)의 한 방법이다. 
훈련 데이터와 정답을 주고서 프로그램을 학습시키는 것이다. 
학습 후 검증 데이터를 통해 적절하게 학습되었는지 모델을 검증하는 과정을 거친다. 
사람으로 비유하자면 학생이 학교에서 수업을 듣고(훈련 데이터로부터의 학습), 시험을 통해 평가(모델 검증)받는 것이다. 분류나 회귀 작업들이 대표적인 지도 학습의 예시이다.    

&nbsp;
&nbsp;

**주요 분류 (Task Types)**

**분류 (Classification)**: 데이터를 정해진 카테고리(범주)로 분류합니다. (예: 스팸 메일 분류, 질병 유무 진단, 이미지 객체 인식)  
**회귀 (Regression)**: 연속적인 수치를 예측합니다. (예: 주가 예측, 부동산 가격 예측, 온도 예측)    

&nbsp;
&nbsp;

**주요 알고리즘 (Algorithms)**

**선형 회귀 (Linear Regression)**: 변수 간의 선형 상관관계를 모델링하여 수치를 예측

**로지스틱 회귀 (Logistic Regression)**: 데이터가 특정 범주에 속할 확률을 0과 1 사이로 예측하여 분류

**K-최근접 이웃 (KNN, K-Nearest Neighbors)**: 새로운 데이터와 가장 가까운 k개의 학습 데이터를 기준으로 분류 또는 회귀

**서포트 벡터 머신 (SVM, Support Vector Machine)**: 데이터 클래스 간의 마진(여백)을 최대화하는 경계선을 찾아 분류

**결정 트리 (Decision Tree) & 랜덤 포레스트 (Random Forest)**: 나무 구조로 질문을 던져 분류/회귀를 수행하며, 여러 트리를 합쳐 정확도를 높인 모델

**인공신경망 (Neural Network/Deep Learning)**: 사람의 뇌 구조를 모방하여 복잡한 패턴을 학습   





