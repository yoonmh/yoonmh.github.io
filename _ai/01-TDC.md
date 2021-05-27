---
title: "TensorFlow Developer Certificate"
layout: single
---

Cousera에서 운영하는 <TensorFlow Developer Certificate> 과정의 강좌 및 소스코드 입니다.
  
## 목차

### Class 1. Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning
* W-1. A New Programming Paradigm
  1. A primer in machine learning
  2. The ‘Hello World’ of neural networks
  3. Working through ‘Hello World’ in TensorFlow and Python
* W-2. Introduction to Computer Vision
  1. An Introduction to computer vision
  2. Writing code to load training data2m
  3. Coding a Computer Vision Neural Network
  4. Walk through a Notebook for computer vision
  5. Using Callbacks to control training
  6. Walk through a notebook with Callbacks
* W-3. Enhancing Vision with Convolutional Neural Networks
  1. What are convolutions and pooling?
  2. Implementing convolutional layers
  3. Implementing pooling layers
  4. Improving the Fashion classifier with convolutions
  5. Walking through convolutions
* W-4. Using Real-world Images
  1. Inderstanding ImageGenerator
  2.Defining a ConvNet to use complex images
  3.Training the ConvNet with fit_generator
  4.Walking through developing a ConvNet
  5.Walking through training the ConvNet with fit_generator
  6.Adding automatic validation to test accuracy
  7.Exploring the impact of compressing images

### Class 2. Convolutional Neural Networks in TensorFlow
* W 1. Exploring a Larger Dataset
  1.Training with the cats vs. dogs dataset
  2.Working through the notebook
  3.Fixing through cropping
  4.Visualizing the effect of the convolutions
  5.Looking at accuracy and loss
* W 2. Augmentation: A technique to avoid overfitting
  1.Introducing augmentation
  2.Coding augmentation with ImageDataGenerator
  3.Demonstrating overfitting in cats vs. dogs
  4.Adding augmentation to cats vs. dogs
  5.Exploring augmentation with horses vs. humans
* W 3. Transfer Learning
  1.Understanding transfer learning: the concepts
  2.Coding transfer learning from the inception mode
  3.Coding your own model with transferred features
  4.Exploring dropouts
  5.Exploring Transfer Learning with Inception

   W 4. Multiclass Classifications
      1.Moving from binary to multi-class classification
      2.Explore multi-class with Rock Paper Scissors dataset
      3.Train a classifier with Rock Paper Scissors
      4.Test the Rock Paper Scissors classifier

Class 3. Natural Language Processing in TensorFlow

   W 1. Sentiment in text
      Introduction
      Word based encodings
      Using APIs
      Notebook for lesson 
      Text to sequence
      Looking more at the Tokenizer
      Padding
      Notebook for lesson 
      Sarcasm, really?
      Working with the Tokenizer
      Notebook for lesson
      News headlines dataset for sarcasm detection

   W 2. Word Embeddings
      Introduction
      The IMBD dataset
      Looking into the details
      How can we use vectors?
      More into the details
      Notebook for lesson 
      Remember the sarcasm dataset?
      Building a classifier for the sarcasm dataset
      Let’s talk about the loss function
      Pre-tokenized datasets

   W 3. Sequence models
      Introduction
      LSTMs
      Implementing LSTMs in code
      Accuracy and loss
      A word from Laurence
      Looking into the code
      Using a convolutional network
      Going back to the IMDB dataset
      Tips from Laurence

   W 4. Sequence models and literature
      Introduction
      Looking into the code
      Training the data
      More on training the data
      Notebook for lesson 
      Finding what the next word should be
      Example
      Predicting a word
      Poetry!
      Looking into the code
      Laurence the poet!
      Your next task

Class 4. Sequences, Time Series and Prediction
   W 1. Sequences and Prediction
      Time series examples
	주식가격, 일기예보, Moor's law(Density vs. year), 컴퓨터공학 박사(tylervigen.com)
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

   W 2. Deep Neural Networks for Time Series
      Preparing features and labels
      Preparing features and labels
      Feeding windowed dataset into neural network
      Single layer neural network
      Machine learning on time windows
      Prediction
      More on single layer neural network
      Deep neural network training, tuning and prediction
      Deep neural network

   W 3. Recurrent Neural Networks for Time Series
      Conceptual overview
      Shape of the inputs to the RNN
      Outputting a sequence
      Lambda layers
      Adjusting the learning rate dynamically
      RNN
      LSTM
      Coding LSTMs
      More on LSTM

   W 4. Real-world time series data
      Convolutions
      Bi-directional LSTMs
      LSTM
      Real data - sunspots
      Train and tune the model
      Prediction
      Sunspots
      Combining our tools for analysis
      Congratulations!
