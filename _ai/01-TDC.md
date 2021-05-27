---
title: "TensorFlow Developer Certificate"
layout: single
---

> Cousera에서 운영하는 "TensorFlow Developer Certificate" 과정의 강좌 및 소스코드 입니다.
  
## 목차

### Class 1. AI, 머신러닝, 딥러닝
* W-1. 프로그래밍 패러다임
  1. 머신러닝 기초 ([Video](https://drive.google.com/file/d/1Cf_9DH7KWcLz7YJ-W4DHGngaMrVE15pX/view?usp=sharing))
  2. 신경망의 ‘Hello World’ ([Video](https://drive.google.com/file/d/1CemGe4AnOjuOm7OE4C5AycbLzrP-D565/view?usp=sharing))
  3. 텐서플로우 ‘Hello World’ 작업하기 ([Video](https://drive.google.com/file/d/1CfQYOuy4BD6H_bPzh4eYMph-2dnyBQCC/view?usp=sharing))
* W-2. 컴퓨터 비전 
  1. 컴퓨터 비전 소개 ([Video](https://drive.google.com/file/d/1CjA1cS5tW3S4FeRniPYP_bnluFsgkLPr/view?usp=sharing))
  2. Writing code to load training data2m
  3. 컴퓨터 비전 신경망 코딩 ([Video]())
  4. 컴퓨터 비전 노트북 작업 ([Video]())
  5. 학습을 콘트롤하기 위한 Callback 사용 ([Video]())
  6. Callback으로 노트북 작업하기 ([Video]())
* W-3. CNN으로 비전 향상
  1. Convolution과 ooling 이란? ([Video]())
  2. Convolutional layer 구현 ([Video]())
  3. Pooling layer 구현 ([Video]())
  4. 컨벌루션으로 Fashion classifier 성능향상 ([Video]())
  5. 컨벌루션 작업하기 ([Video]())
* W-4. 실생활 이미지 사용
  1. ImageGenerator 이해 ([Video]())
  2. 복잡한 이미지에 사용하기 위한 ConvNet 정의 ([Video]())
  3. fit_generator와 함께 ConvNet 학습 ([Video]())
  4. ConvNet 작업하기 ([Video]())
  5. fit_generator와 함께 ConvNet 학습 작업하기 ([Video]())
  6. 테스트 정확도에 대한 자동 검증 ([Video]())
  7. 이미지 압축 효과 탐색 ([Video]())

### Class 2. 턴서플로우에서 CNN
* W-1. 대규모 Dataset 사용
  1. 고양이와 개 dataset 학습 ([Video]())
  2. 노트북 작업하기 ([Video]())
  3. Fixing through cropping
  4. 컨벌루션 효과 시각화 ([Video]())
  5. Accuracy와 loss 관점에서 바라보가 ([Video]())
* W-2. Augmentation: overfitting을 피하는 방법
  1. Augmentation 소개 ([Video]())
  2. ImageDataGenerator로 augmentation 코딩 ([Video]())
  3. 고양이와 개 데이터에서 overfitting 데모 ([Video]())
  4. Adding augmentation to cats vs. dogs
  5. Exploring augmentation with horses vs. humans
* W-3. Transfer Learning
  1. Understanding transfer learning: the concepts
  2. Coding transfer learning from the inception mode
  3. Coding your own model with transferred features
  4. Exploring dropouts
  5. Exploring Transfer Learning with Inception
* W-4. Multiclass Classifications
  1. Moving from binary to multi-class classification
  2. Explore multi-class with Rock Paper Scissors dataset
  3. Train a classifier with Rock Paper Scissors
  4. Test the Rock Paper Scissors classifier

### Class 3. 텐서플로우에서 자연어 처리 (NLP)
* W-1. 문장에서 Sentiment
  1. 서론 ([Video]())
  2. 단어의 encoding ([Video]())
  3. API 사용 ([Video]())
  4. 노트북 예제 ([Video]()) 
  5. Text to sequence
  6. Looking more at the Tokenizer
  7. Padding
  8. Notebook for lesson 
  9. Sarcasm, really?
  10. Working with the Tokenizer
  11. Notebook for lesson
  12. News headlines dataset for sarcasm detection
* W-2. Word Embeddings
  1. 서론 ([Video]())
  2. IMBD dataset ([Video]())
  3. Looking into the details
  4. How can we use vectors?
  5. More into the details
  6. Notebook for lesson 
  7. Remember the sarcasm dataset?
  8. Building a classifier for the sarcasm dataset
  9. Let’s talk about the loss function
  10. Pre-tokenized datasets
* W-3. Sequence 모델
  1. 서론 ([Video]())
  2. LSTM ([Video]())
  3. LSTM 구현 ([Video]())
  4. Accuracy와 loss ([Video]())
  5. A word from Laurence
  6. Looking into the code
  7. Using a convolutional network
      Going back to the IMDB dataset
      Tips from Laurence

* W-4. Sequence 모델과 문학
  1. 서론 ([Video]())
  2. Looking into the code
  3. Training the data
  4. More on training the data
  5. 노트북 예제 ([Video]())
  6. Finding what the next word should be
      Example
      Predicting a word
      Poetry!
      Looking into the code
      Laurence the poet!
      Your next task

### Class 4. Sequences, Time Series & Prediction
* W-1. Sequences and Prediction
  1. Time series의 예 ([Video]())
  2. 주식가격, 일기예보, Moor's law(Density vs. year), 컴퓨터공학 박사(tylervigen.com)
	multivariate time series: birth & death rate in Japan, global temperature, co2 concentration,자동차 운동(longitude, latitude)
	forecasts, imputed data, imputation, 
	tend, seasonality, autocorrelation, noise
	non-stationary time series

      Machine learning applied to time series

      Common patterns in time series
      Introduction to time series
      Train, validation and test sets
	trend+seasonality+noise, naive forecasting, fixed partitioning


      Metrics for evaluating performance
      Moving average and differencing
      Trailing versus centered windows
      Forecasting

* W-2. Deep Neural Networks for Time Series
  1. Preparing features and labels
  2. Preparing features and labels
  3. Feeding windowed dataset into neural network
  4. Single layer neural network
  5. Machine learning on time windows
  6. Prediction
  7. More on single layer neural network
  8. Deep neural network training, tuning and prediction
  9. Deep neural network

* W-3. Time Series를 위한 RNN
  1. 개념 정리 ([Video]())
  2. Shape of the inputs to the RNN
  3. Outputting a sequence
  4. Lambda layers
  5. Adjusting the learning rate dynamically
  6. RNN
  7. LSTM
  8. LSTM 코딩 ([Video]())
  9. More on LSTM

* W-4. 실생활의 time series data
  1. Convolutions
  2. 양방향 LSTM ([Video]())
  3. LSTM
  4. Real data - sunspots
  5. Train and tune the model
  6. Prediction
  7. Sunspots
  8. Combining our tools for analysis
  9. Congratulations!
