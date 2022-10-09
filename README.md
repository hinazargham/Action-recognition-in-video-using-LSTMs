# Action recognition in video using LSTMs


## Classifying videos with an LSTM
We will make use of the UCF101 dataset which was put together by K. Soomro et al. (refer to UCF101: A Dataset of 101 Human Actions Classes From Videos in The Wild, CRCV-TR-12-01, 2012). The dataset is composed of 13,320 segments of video. Each segment contains a person performing one of 101 possible actions. We will classify the videos in two steps. First, we will extract the features and cache them. Once this is done, we will train the LSTM on extracted features. The code is working on Tensorflow version 2.7.1


### Book:
[Hands-On Computer Vision with TensorFlow 2 by Benjamin Planche and Eliot Andres, Published by Packt](https://github.com/PacktPublishing/Hands-On-Computer-Vision-with-TensorFlow-2) (Chapter8)


