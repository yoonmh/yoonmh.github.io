---
title: "Deep Learning Specialization"
layout: single
---

> Deep Learning Specialization

## 1. Neural Networks and Deep Learning
### Week 1 : Introduction to Deep Learning 
* Welcome to DLS
* Introduction to Deep Laerning : [강의자료][11-1]
  * What is a Neural Network?, Supervised Learning with Neural Networks, Why is Deep Learning taking off?
* [Geoffrey Hinton 인터뷰][11-2]

### Week 2 : Neural Network Basics 
* Logistic Regression as a Neural Network : [강의자료][12-1], [참고][12-2]
  * Binary Classification, Logistic Regression, Logistic Regression Cost Function, Gradient Descent, Derivatives, More Derivative Examples, Computation Graph, Derivatives with Computation Graph, LogisticRegreaaion Gradient Descent, Gradient Descent on m Examples
* Python and Vectorization
  * Vectorization, More Vectorization Examples, Vectorizing Logistic Regressipn, Vectorizing Logistic Regressipn Gradient Output
  * [Vectorization 예제][12-3], [Broadcasting 예제][12-4], [Numpy 예제][12-5]
  * [Python Basics 과제][12-6], [Logistic Regression 과제][12-7]
  * [Pieter Abbeel 인터뷰][12-8]

### Week 3 : Shallow Neural Networks 
* Shallow Network : [강의자료][13-1]
  * Neural Network Overview, Neural Network Representation, Computing a Neural Network's Output, Vectoriaing Across Multiple Examples, Explanation of Vectorized Implementation, Activation Functions, Why do you need Non-linear Activation Functions?, Derivatives of Activatio Functions, Gradient Descent for Neural Networks, Backpropagation Intuition, Random Initialization
  * [Planar Data Classification 과제][13-2]
  * [Ian Goodfellow 인터뷰][13-3]

### Week 4 : Deep Neural Networks
* Deep Neural Network : [강의자료][14-1], [참고][14-2]
  * Deep Neural Network, Forward Propagation in Deep Network, Getting your Matrix Dimentions Right, Why Deep Representations?, Building Blocks of Deep Neural Networks, Forward and Backward Propagation
*  [DNN 과제][14-3], [DNN Application 과제][14-4]
* References
  * [NN from Scartch][15-1], [Reference][15-2], [cs231n][15-3], [Autoreload][15-4]

## 2. Improving DNN: Hyperparameter tuning, Regularization, and Optimization
* Practical Aspects of Deep Learning : [강의자료][21-1]
  * Setting up your ML Application : Train/Dev/Test sets, Bias/Variance, Basic Recipe for ML
  * Regularizing your Neural Network : Regularization, Why Regularization Reduces Overfitting?, Dropout Regularization, Undestading Dropout, Other Regularization Methods
  * Setting up your Optimization Problem : Normalizing Inputs, 
  * [Initialization 과제][21-2], [Regularization 과제][21-3], [Gradient 과제][21-4]
  * [Yoshua Bengio 인터뷰][21-5]
* Optimization Algorithms : [강의자료][22-1]
  * Mini-batch Gradient Descent, Understading Mini-batch Gradient Descent, Exponetially Weighed Averages, RMSprop
  * 
  * [Optimization 과제][22-2]
  * [Yuanqing Lin 인터뷰][22-3]
* Hyperparameter Tuning, Batch Normalization and Programming Frameworks : [강의자료][23-1]
  * Hyperparameter Tuning : Tuining Process, Using an Appropriate Scale to pick Hyperparameters, Hyperparameter Tuing in pRactice
  * Batch Normalization : Normalizing Activations
  * Multi-class Classification : 
  * [Tensorflow 과제][23-2]
* References
  * [자동미분][24-1], [GradientTape][24-2]
  
## 3. Structuring Machine Learning Projects
* ML Strategy : [강의자료][31-1]
  * [Andrej Karpathy 인터뷰][31-2]
* Error Analysis : [강의자료][32-1]
  * [Ruslan Salakhutdinov 인터뷰][32-2]

## 4. Convolutional Neural Networks
* Foundations of CNN : [강의자료][41-1]
  * [CNN 과제][41-2], [Conv Application 과제][41-3]
  * [Yann LeCun 인터뷰][41-4]
* Deep Convolutional Models : [강의자료][42-1]
  * [Residual Network 과제][42-2], [Transfer Learning 과제][42-3]
* Object Detection : [강의자료][43-1]
  * [Car detection 과제][43-2], [Image Segmentation 과제][43-3]
* Special Applications : [강의자료][44-1]
  * [Face Recognition 과제][44-2], [Art Generation 과제][44-3]
* References
  * [Sequential 모델][45-1], [Functional API][45-2]
  * [resnet50][45-3], [YAD2k][45-4], [YOLO][45-5]
  * [facenet][45-6], [Face Recognition][45-7], [keras-facenet][45-8]
  * [Artistic Style][45-9], [artistic style transfer][45-10], [MatConvNet][45-11]
    
## 5. Sequence Models
* Recurrent Neural Networks : [강의자료][51-1]
  * GRU : [Cho][51-r1], [Chung][51-r2]
  * LSTM : [Hochreiter][51-r3]
  * [RNN 과제][51-2], [Dinosaurus Island 과제][51-3], [Jazz Improvisation 과제][51-4]
* Natural Language Processing & Word Embedding : [강의자료][52-1]
  * [Word embeddings][52-r1], [Language model][52-r2], [Skip-gram][52-r3], [Negative sampling][52-r4], [GloVe][52-r5], [Debiasing][52-r6]
  * [Word Vectors 과제][52-2], [Emojify 과제][52-3]
* Sequence Models & Attention Mechanism : [강의자료][53-1]
  * Sequence to Sequence : [Sutskver][53-r1], [Cho][53-r2]
  * Image captioning : [Mao][53-r3], [Vinyals][53-r4], [Karpathy][53-r5]
  * Blau score : [Papineni][53-r6]
  * Attention : [Bahdanau][53-r7], [Xu][53-r8]
  * [Machine Translation 과제][53-2], [Word Detection 과제][53-3]
* Transformer Network : [강의자료][54-1]
  * [Transformers 과제][54-2], [Transformer Pre-processing 과제][54-3], [Transformer Application #1][54-4], [Transformer Application #2][54-5]

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
