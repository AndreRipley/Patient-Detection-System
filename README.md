# Patient Detection System

This is the repo for alerting nurses wheter a patient gets our of their hospital bed unsuprivsed. This will be implementing computer vision techniques such as action recogonition, human recogntion models, and use of RNNs.


### Prerequisites

You will need:

OpenCV (https://opencv.org/)
TensorFlow (https://www.tensorflow.org/install/)
Keras (https://keras.io/#installation)
Python3+ (https://www.python.org/downloads/)

## Main Classifier
The system will comprise of 3 classifiers to saftey reason to give us the lowest chance of a false detection. It will use facial recognition, human recognition, and action recognition.

## Facial Recognition

Here is an output of the facial recognition. This will be used as one of the 3 classifiers we will use.
![screen shot 2019-01-22 at 12 32 34 am](https://user-images.githubusercontent.com/39922134/51514362-5d314a00-1ddd-11e9-8f04-21efe5d879e9.png)

![screen shot 2019-01-22 at 12 32 16 am](https://user-images.githubusercontent.com/39922134/51514379-6de1c000-1ddd-11e9-8904-ebfcf92cf443.png)

## Human Detection
I will be using OpenCV for human detections models. There are two approaches for human detection models which is using Haar Cascades and HOG or Deep Convolutional Nueral Networks. The more accurate model would be the implementation of Deep Convolutional Nueral Networks. However this approaches has a drawback of high GPU usage. 
