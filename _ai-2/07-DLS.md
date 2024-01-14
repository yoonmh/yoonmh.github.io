---
title: "Deep Learning Specialization"
layout: single
---

> Deep Learning Specialization

## Class 1. Neural Networks and Deep Learning
### (1) Introduction to Deep Learning 
* [Lecture Notes][11-1]
* Introduction to Deep Laerning
  * 1-What is a Neural Network?, 2-Supervised Learning with Neural Networks, 3-Why is Deep Learning taking off?
* [Geoffrey Hinton 인터뷰][11-2]

### (2) Neural Network Basics 
* [Lecture Notes][12-1]
* Logistic Regression as a Neural Network [참고][12-2]
  * 1-Binary Classification, 2-Logistic Regression, 3-Logistic Regression Cost Function, 4-Gradient Descent, 5-Derivatives, 6-More Derivative Examples, 7-Computation Graph, 8-Derivatives with Computation Graph, 9-LogisticRegreaaion Gradient Descent, 10-Gradient Descent on m Examples
* Python and Vectorization
  * 1-Vectorization, 2-More Vectorization Examples, 3-Vectorizing Logistic Regressipn, 4-Vectorizing Logistic Regressipn Gradient Output, 5-Broadcasting in Python, 6-A Note on Python/Numpy Vectors, 7-Quick tour of Jupyter/iPython Notebooks, 8-Explanation of Logistic Regression Cost Function
* Programming Assignments
  * [Python Basics with Numpy][12-31], [Logistic Regression with a Neural Network Mindset][12-7]
  * [Numpy][12-3], [Broadcasting 예제][12-4], [Numpy 예제][12-5], [Python Basics 과제][12-6], 
* [Pieter Abbeel 인터뷰][12-8]
* References : [NN from Scartch][15-1], [StackExchange][15-2]

### (3) Shallow Neural Networks 
* [Lecture Notes][13-1]
* Shallow Network
  * 1-Neural Network Overview, 2-Neural Network Representation, 3-Computing a Neural Network's Output, 4-Vectorizing Across Multiple Examples, 5-Explanation of Vectorized Implementation, 6-Activation Functions, 7-Why do you need Non-linear Activation Functions?, 8-Derivatives of Activation Functions, 9-Gradient Descent for Neural Networks, 10-Backpropagation Intuition, 11-Random Initialization
* Programming Assignments : [Planar Data Classification with One Hidden Layer][13-2],
* [Ian Goodfellow 인터뷰][13-3]
* References : [cs231n][15-3]

### (4) Deep Neural Networks
* Deep Neural Network : [강의자료][14-1], [참고][14-2]
  * 1-Deep L-layer Neural Network, 2-Forward Propagation in a Deep Network, 3-Getting your Matrix Dimentions Right, 4-Why Deep Representations?, 5-Building Blocks of Deep Neural Networks, 6-Forward and Backward Propagation
  * [Feedforward Neural Networks in Depth][147]
  * 7-Parameters vs. Hyperparameters, 8-What does this have to do with the brain?
* Programming Assignments : [DNN 과제][14-3], [DNN Application 과제][14-4]
* References : [Autoreload][15-4]

[147]: https://community.deeplearning.ai/t/feedforward-neural-networks-in-depth/98811

## Class 2. Improving DNN: Hyperparameter Tuning, Regularization, and Optimization
### (1) Practical Aspects of Deep Learning 
* [Lecture Notes][21-1]
* Setting up your Machine Learning Application
  * 1-Train/Dev/Test sets, 2-Bias/Variance, 3-Basic Recipe for ML
* Regularizing your Neural Network
  * 4-Regularization, 5-Why Regularization Reduces Overfitting?, 6-Dropout Regularization, 7-Undestading Dropout, 8-Other Regularization Methods
* Setting up your Optimization Problem
  * 9-Normalizing Inputs, 10-Vanishing/Exploding Gradients, 11-Weight Initialization for Deep Networks, 12-Numerical Appoximation of Gradients, 13-Gradient Checking, 14-Gradient Checking Implementation Notes
* Programming Assignments
  * [Initialization 과제][211] ([Code][21-2]), [Regularization 과제][212] ([Code][21-3]), [Gradient 과제][213] ([Code][21-4])
* [Yoshua Bengio 인터뷰][21-5]

[211]: https://drive.google.com/file/d/1ZQmW5txxc7o1NC9P2_cJwuKOwe4kJy_z/view
[212]: https://drive.google.com/file/d/1ZZROlmotrNXg-ICk0zSgLCrt3SI5Wsx1/view
[213]: https://drive.google.com/file/d/1ZddGlNvRM7DdQclacBdpt36QznDS4_SU/view

### (2) Optimization Algorithms
* [Lecture Notes][22-1]
* Optimization Algorithm
  * 1-Mini-batch Gradient Descent, 2-Understading Mini-batch Gradient Descent, 3-Exponentially Weighted Averages, 4-Understanding Exponentially Weighted Averages, 5-Bias Correction in Exponentially Weighted Averages
  * 6-Gradient Descent with Momentum, 7-RMSprop, 8-Adam Optimization Algorithm, 9-Learning Rate Decay, 10-Problem of Local Optima
* Programming Assignments : [Optimization 과제][221] ([Code][22-2])
* [Yuanqing Lin 인터뷰][22-3]

[221]: https://drive.google.com/file/d/1_Du_fWSQ1BvY4PWMPh5wBGN5E9Glj6j0/view

### (3) Hyperparameter Tuning, Batch Normalization and Programming Frameworks
* [Lecture Notes][23-1]
* Hyperparameter Tuning
  * 1-Tuining Process, 2-Using an Appropriate Scale to pick Hyperparameters, 3-Hyperparameter Tuing in pRactice: Pandas vs Cavlar
* Batch Normalization
  * 4-Normalizing Activations in a Network, 5-Fitting Batch Norm into a Neural Network, 6-Why does Batch Norm work?, 7-Batch Norm at Test Time
* Multi-class Classification
  * 8-Softmax Regression, 9-Training a Softmax Classifier
* Introduction to Programming Frameworks
  * 10-Deep Learning Frameworks, 11-Tensorflow
* Programming Assignments : [Tensorflow 과제][23-2]
* References : [자동미분][24-1], [GradientTape][24-2]

## Class 3. Structuring Machine Learning Projects
### (1) ML Strategy
* [Lecture Notes][31-1]
* Introduction to ML Strategy
  * 1-Why ML Strategy, 2-Orthogonalization
* Setting Up your Goal
  * 3-Single Number Evaluation Metric, 4-Satisficing and Optimizing Metric, 5-Train/Dev/Test Distributions, 6-Size of the Dev and Test Sets, 7-When to Change Dev/Test Sets and Metrics?
* Comparing to Human-level Performance
  * 8-Why Human-level Performance?, 9-Avoidable Bias, 10-Understanding Human-level Performance, 11-Surpassing Human-level Performance, 12-Improving your Model Performance
* [Machine Learning Flight Simulator][311]
* [Quiz][312]
* [Andrej Karpathy 인터뷰][31-2]

### (2) ML Strategy
* [Lecture Notes][32-1]
* Error Analysis
  * 1-Carrying Out Error Analysis, 2-Cleaning Up Incorrectly Labeled Data, 3-Build your First System Quickly, then Iterate
* Mismatched Training and Dev/Test Set
  * 4-Training and Testing on Different Distributions, 5-[Bias and Variance with Mismatched Data Distributions][325], 6-Addressing Data Mismatch
* Learning from Multiple Tasks
  * 7-Transfer Learning, 8-Multi-task Learning
* End-to-end Deep Learning
  * 9-What is End-to-end Deep Learning?, 10-Whether to use End-to-end Deep Learning
* [Autonomous Driving][321]
* [Ruslan Salakhutdinov 인터뷰][32-2]

[311]: https://drive.google.com/file/d/1_IoJcu6CAg9yg2ciJcD0DmcDKzgyRcE_/view
[312]: https://drive.google.com/file/d/1_QTN27CdWoOliHZo9jOBP2jI0sqQRHM0/view
[325]: https://drive.google.com/file/d/1_Ra3HL820QpBBoSgS-EpLBDOHApFnMtc/view
[321]: https://drive.google.com/file/d/1_Tc6OCWvp9CkSDIqZr6F7alXhCfTOAHp/view

## 4. Convolutional Neural Networks
### (1) Foundations of Convolutional Neural Networks
* [Lecture Notes][41-1]
* Convolutional Neural Networks
  * Computer Vision, Edge Detection Example, More Edge Detection, Padding, Strided Convolutions, Convolutions Over Volume, One Layer of a Convolutional Network, Simple Convolutional Network Example, Pooling Layers, CNN Example, Why Convolutions?
* Programming Assignments
  * [Convolutional Model][41-2], [Convolutional Model Application][41-3]
* References : [Sequential 모델][45-1], [Functional API][45-2]
* [Yann LeCun 인터뷰][41-4]

### (2) Deep Convolutional Models: Case Study 
* [Lecture Notes][42-1]
* Case Studies
  * Why look at case studies?, Classic Networks, ResNets, Why ResNets Work?, Networks in Networks and 1x1 Convolutions, Inception Network Motivation, Inception Network, MobileNet, MobileNet Architecture, EfficientNet
* Practical Advive for Using ConvNets
  * Using Open-Source Implementation, Transfer Learning, Data Augmentation, State of Computer Vision
* Programming Assignments
  * [Residual Networks][42-2], [Transfer Learning with MobileNet][42-3]

### (3) Object Detection
* [Lecture Notes][43-1]
* Detection Algorithms
  * Object Localization, Landmark Detection, Object Detection, Convolutional Implementation of Sliding Windows, Bounding Box Predictions, Intersection Over Union, Non-max Suppression, Anchor Boxes, YOLO Algorithm, Region Proposals, Semantic Segmentation with U-Net, Transpose Convolutions, U-Net Architecture Intuition, U-Net Architecture
* Programming Assignments  
  * [Car detection with YOLO][43-2], [Image Segmentation with U-Net][43-3]

### (4) Special Applications : Face Recognition & Neural Style Transfer
* [Lecture Notes][44-1]
* Face Recognition
  * What is Face Recognition?, One Shot Learning, Siamese Network, Triplet Loss, Face Verification and Binary Classification
* Neural Style Transfer
  * What is Neural Style Transfer?, What are deep ConvNets learning?, Cost Function, Content Cost Function, Style Cost Function, 1D and 3D Generalizations
* Programming Assignments
  * [Face Recognition][44-2], [Art Generation with Neural Style Transfer][44-3]
* References
  * [resnet50][45-3], [YAD2k][45-4], [YOLO][45-5]
  * [facenet][45-6], [Face Recognition][45-7], [keras-facenet][45-8]
  * [Artistic Style][45-9], [artistic style transfer][45-10], [MatConvNet][45-11]
    
## 5. Sequence Models
### (1) Recurrent Neural Networks
* [Lecture Notes][51-1]
* Recurrent Neural Networks
  * Why Sequence Models?, Notation, Recurrent Neural Network Model, Backpropagation Through Time, Different Types of RNNs, Language Model and Sequence Generation, Sampling Novel Sequences, Vanishing Gradients with RNNs, Gated Recurrent Unit (GRU), Long Short Term Memory (LSTM), Bidirectional RNN, Deep RNNs
* References
  * GRU : [Cho][51-r1], [Chung][51-r2]
  * LSTM : [Hochreiter][51-r3]
* Programming Assignments  
  * [Building your RNN][51-2], [Dinosaur Island-Character-Level Language Modeling][51-3], [Jazz Improvisation with LSTM][51-4]

### (2) Natural Language Processing & Word Embedding 
* [Lecture Notes][52-1]
* Introduction to Word Embeddings
  * Word Representation, Using Word Embeddings, Properties of Word Embeddings, Embedding Matrix
* Learning Word Embeddings: Word2Vec & Glove
  * Learning Word Embeddings, Word2Vec, Negative Sampling, GloVe Word Vectors
* Applications Using Word Embeddings
  * Sentiment Classification, Debiasing Word Embeddings
* References
  * [Word embeddings][52-r1], [Language model][52-r2], [Skip-gram][52-r3], [Negative sampling][52-r4], [GloVe][52-r5], [Debiasing][52-r6]
* Programming Assignments
  * [Operations on Word Vectors - Debiasing][52-2], [Emojify][52-3]

### (3) Sequence Models & Attention Mechanism 
* [Lecture Notes][53-1]
* Various Sequence to Sequence Architectures
  * Basic Models, Picking the Most Likely Sentence, Beam Search, Refinements to Beam Search, Error Analysis in Beam Search, Bleu Score, Attention Model Intuition, Attention Model
* Speech Recognition - Audio Data
  * Speech Recognition, Trigger Word Detection
* References
  * Sequence to Sequence : [Sutskver][53-r1], [Cho][53-r2]
  * Image captioning : [Mao][53-r3], [Vinyals][53-r4], [Karpathy][53-r5]
  * Blau score : [Papineni][53-r6]
  * Attention : [Bahdanau][53-r7], [Xu][53-r8]
* Programming Assignments 
  * [Neural Machine Translation][53-2], [Trigger Word Detection][53-3]

### (4) Transformer Network 
* [Lecture Notes][54-1]
* Transformers
  * Transformer Network Intuition, Self-Attention, Multi-Head Attention, Transformer Network
* Programming Assignments 
  * [Transformers Architecture with TensorFlow][54-2], [Transformer Pre-processing][54-3], [Transformer Application #1][54-4], [Transformer Application #2][54-5]

[51-r1]: https://aclanthology.org/N13-1090/
[51-r2]: https://arxiv.org/abs/1412.3555
[51-r3]: https://drive.google.com/file/d/1TStzOWFm0mnWLzbgWpHN7Hainj-L9tF7/view
[52-r1]: https://drive.google.com/file/d/1ToGCqoS7iUDyB6zVSaxdWI90e-bFIe7e/view
[52-r2]: https://drive.google.com/file/d/1TfY3Cl0g6vfK8mVxmPMI6Mpd0hTuY12U/view
[52-r3]: https://arxiv.org/abs/1301.3781
[52-r4]: https://arxiv.org/abs/1310.4546
[52-r5]: https://aclanthology.org/D14-1162/
[52-r6]: https://arxiv.org/abs/1607.06520
[53-r1]: https://arxiv.org/abs/1409.3215
[53-r2]: https://arxiv.org/abs/1406.1078
[53-r3]: https://arxiv.org/abs/1412.6632
[53-r4]: https://arxiv.org/abs/1411.4555
[53-r5]: https://arxiv.org/abs/1412.2306
[53-r6]: https://aclanthology.org/P02-1040/
[53-r7]: https://arxiv.org/abs/1409.0473
[53-r8]: https://proceedings.mlr.press/v37/xuc15.html

[11-1]: https://drive.google.com/file/d/1GIEIQCNqA3ZGAeLyKJNwJQq9bZ0p8DOH/view?usp=drive_link
[11-2]: https://drive.google.com/file/d/1GgookSh9VQFDr1q6Uf3B9uGPJPyJgKv8/view?usp=drive_link
[12-1]: https://drive.google.com/file/d/1GQooZ1TYIUsEihFhft_McLpeVAMke2Rk/view?usp=drive_link
[12-2]: https://community.deeplearning.ai/t/derivation-of-dl-dz/165
[12-3]: https://colab.research.google.com/drive/1I4NRAAdoLVmcUjEMIqKIx3oTpARZL4Sa
[12-31]: https://colab.research.google.com/drive/1H7OSKj3HQ2ZR61dwUxvMHd15qc3d7Rrh
[12-4]: https://colab.research.google.com/drive/18bajA90zXoFnkdCn8dW1Nd7nBN_-yPVP
[12-5]: https://colab.research.google.com/drive/14GlLRgu9xmr5k40eLpqFqYrodbr2qDcz
[12-6]: https://colab.research.google.com/drive/1H7OSKj3HQ2ZR61dwUxvMHd15qc3d7Rrh
[12-7]: https://colab.research.google.com/drive/1HAj9t9pCFZtTPVhRIumzEoB_sbXapVva
[12-8]: https://drive.google.com/file/d/1HHvhm2FQzKWNaANGKilPtDurdZLFVeew/view?usp=drive_link
[13-1]: https://drive.google.com/file/d/1GaQCR_tfwMDEGIH_Ud05zcm8r3Bbg1NU/view?usp=drive_link
[13-2]: https://colab.research.google.com/drive/1HQ2NRUjEHWEPVDpYnFkEqH-VtNUrfOdQ
[13-3]: https://drive.google.com/file/d/1HkxOm2Kx72VUz5CXtJ9u4MI0xJoNiB_o/view?usp=drive_link
[14-1]: https://drive.google.com/file/d/1G_VPlEE9N3hJaOXpB-UtgtdRN_QnUHWS/view?usp=drive_link
[14-2]: https://community.deeplearning.ai/t/feedforward-neural-networks-in-depth/98811
[14-3]: https://colab.research.google.com/drive/1HsUgpY3KSelhA8P2koPXYi9cwq8CMhk_
[14-4]: https://colab.research.google.com/drive/1HvbJWiWqTdeJu4aV-mHV8v1QSkEN1ZqA
[15-1]: https://github.com/dennybritz/nn-from-scratch
[15-2]: https://stats.stackexchange.com/questions/211436/why-normalize-images-by-subtracting-datasets-image-mean-instead-of-the-current
[15-3]: https://cs231n.github.io/neural-networks-case-study/
[15-4]: https://stackoverflow.com/questions/1907993/autoreload-of-modules-in-ipython
[21-1]: https://drive.google.com/file/d/1IKyPKCe7f0Q6gmq8qLrY6Ugxq7bBTyp0/view?usp=drive_link
[21-2]: https://colab.research.google.com/drive/1Ies2tpfcc2kJXcjUTAKqJ0CnzaFfTqcz
[21-3]: https://colab.research.google.com/drive/1Ipr8JJ0U1wlTFfT8C-DQOQOXd4kOsIR2
[21-4]: https://colab.research.google.com/drive/1J1fWjDPUL5nLCWEYWumPlDIB2YV-W4bV
[21-5]: https://drive.google.com/file/d/1JAyPdj8tN38F8oG8PEK1277ja_oO2tNv/view?usp=drive_link
[22-1]: https://drive.google.com/file/d/1ICGK395VZaVTXwGVSBwC0xfUDVP1HZad/view?usp=drive_link
[22-2]: https://colab.research.google.com/drive/1JXN-UbCrr3t2N1fakqiC9Gbts6aCHESc
[22-3]: https://drive.google.com/file/d/1JemjfEhMNvpVIp1v1Qx70IbpSlSw972n/view?usp=drive_link
[23-1]: https://drive.google.com/file/d/1ICv7Z3kpVzuBv1pFZbj6H3PMyGSftO4G/view?usp=drive_link
[23-2]: https://colab.research.google.com/drive/1JmV1ZgSOzDAgfACoGxdic2vjLgV4pbiE
[24-1]: https://www.tensorflow.org/guide/autodiff?hl=ko
[24-2]: https://www.tensorflow.org/api_docs/python/tf/GradientTape
[31-1]: https://drive.google.com/file/d/1KwUCbd59y3A_cjCM9vVKKngs0pvaOenB/view?usp=drive_link
[31-2]: https://drive.google.com/file/d/1LJESZwfmkXvmp6ECesCKhyU_qb3bF1wO/view?usp=drive_link
[32-1]: https://drive.google.com/file/d/1K9-P63F3Wl3c99d_rD2F-G4FsRq1v7Mp/view?usp=drive_link
[32-2]: https://drive.google.com/file/d/1OG-s8eEKVSxQhWFzRrYvPVcRTMjzwcwt/view?usp=drive_link
[41-1]: https://drive.google.com/file/d/1LfduIpnUaja698ASE_0LVOcF5S17O68v/view?usp=drive_link
[41-2]: https://colab.research.google.com/drive/1LoqWsrqUuni0RhadykSUDDQvABXD8-iu
[41-3]: https://colab.research.google.com/drive/1M50_9TUqiL5amrdHT5d3HKrdJdPKIAKc
[41-4]: https://drive.google.com/file/d/1M9J0yS-3mQr2lQz2pmV7U6y5G69j3DJc/view?usp=drive_link
[42-1]: https://drive.google.com/file/d/1LdpL5yeo2BLw88jWFRZ7DIvyNhg4EfM8/view?usp=drive_link
[42-2]: https://colab.research.google.com/drive/1MLVW0StAsrfmI9wpZPoZOoQUV9tuPu_I
[42-3]: https://colab.research.google.com/drive/1MMAdNQ6aKMVyTBOTfW1hGSIo3b4XAbfd
[43-1]: https://drive.google.com/file/d/1LanuOxXXHdDUFy-SAVWE4trgX13_lh3Z/view?usp=drive_link
[43-2]: https://colab.research.google.com/drive/1MMPuw5iaE4Z0JLwRi-g3LYKM_4mLCPrH
[43-3]: https://colab.research.google.com/drive/1MVCtJt7A4OhB-RCziHZmUWbHrrv8rLS4
[44-1]: https://drive.google.com/file/d/1LhlM1iq6DVnH4p7w4SSZIuGf36S4VUUi/view?usp=drive_link
[44-2]: https://colab.research.google.com/drive/1MYCIUg6l7ypSKTs9SOOuD-jWL7Nf-Y8M
[44-3]: https://colab.research.google.com/drive/1MbUxE3kb-r7sqZ3Ifho_7xA3ZjoCExgS
[45-1]: https://www.tensorflow.org/guide/keras/sequential_model?hl=ko
[45-2]: https://www.tensorflow.org/guide/keras/functional?hl=ko
[45-3]: https://github.com/fchollet/deep-learning-models/blob/master/resnet50.py
[45-4]: https://github.com/allanzelener/YAD2K
[45-5]: https://pjreddie.com/darknet/yolo/
[45-6]: https://github.com/davidsandberg/facenet
[45-7]: https://machinelearningmastery.com/how-to-develop-a-face-recognition-system-using-facenet-in-keras-and-an-svm-classifier/
[45-8]: https://github.com/nyoki-mtl/keras-facenet/blob/master/notebook/tf_to_keras.ipynb
[45-9]: http://www.chioka.in/tensorflow-implementation-neural-algorithm-of-artistic-style
[45-10]: https://harishnarayanan.org/writing/artistic-style-transfer/
[45-11]: https://www.vlfeat.org/matconvnet/pretrained/
[51-1]: https://drive.google.com/file/d/1G50WzzGlu4Hh2K8cxcM255YbgBJ1FaYi/view?usp=drive_link
[51-2]: https://colab.research.google.com/drive/1N-r18MJ0hbB5-2flnsF82ADwf1Djutk3
[51-3]: https://colab.research.google.com/drive/1N3uwy3p3JLtpE1HpRpqcRdFYvbspe8Am
[51-4]: https://colab.research.google.com/drive/1N9Eg6S2HarGpKyQyvp9A4pRJqvwvTnfs
[52-1]: https://drive.google.com/file/d/1G5ejvPYKFa6AAISWf6ubfi3VFwPe1J2C/view?usp=drive_link
[52-2]: https://colab.research.google.com/drive/1NHAoiV8MUZ7HCi7jS3Gk3QDW6Xdi4Mhv
[52-3]: https://colab.research.google.com/drive/1NJyeybUdXxO1mVTVIhSybViQl9qn-EbT
[53-1]: https://drive.google.com/file/d/1FzaVhZ7WOK3TZ8t5B6SJqtbojnmIOryG/view?usp=drive_link
[53-2]: https://colab.research.google.com/drive/1NUrOglM6pCm83jrZGZ2LoP_J-bS3pTPR
[53-3]: https://colab.research.google.com/drive/1NXfle1h-biEOA-BjoRCRsgvQa1gNlJbZ
[54-1]: https://drive.google.com/file/d/1G-RVhhBS9PLenWHcTaQwyVrcefH2DO0r/view?usp=drive_link
[54-2]: https://colab.research.google.com/drive/1NipRiTYbUf_VM4RmxUzdjdTOI45xGnA-
[54-3]: https://colab.research.google.com/drive/1NnUxGfoeiZxWQxqXu29L1L_mwyHTytQ8
[54-4]: https://colab.research.google.com/drive/1O5x0Q20JQCiO_XKpy4KhCh0oyvzJa0AL
[54-5]: https://colab.research.google.com/drive/1O8z8hbelAhmjo5c9og2xLxKPCEDAdvxE
