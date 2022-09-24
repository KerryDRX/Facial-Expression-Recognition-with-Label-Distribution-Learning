<h1 align="center"> Facial Expression Recognition with Label Distribution Learning </h1> <br>

<p align="center">
  <img src="https://www.pandasecurity.com/en/mediacenter/src/uploads/2019/03/pandasecurity-facial-recognition.jpg">
</p>

<div style="text-align: right"> Image Source: https://www.pandasecurity.com/en/mediacenter/security/facial-recognition-software/
</div>


# Objectives
This research project is focused on **Facial Expression Recognition (FER)** technology. Deep learning models for human emotion
prediction based on facial expressions are constructed and optimized based on several different model architectures,
and many optimization techniques are carried out with their effectiveness evaluated in
the model training process. This project also investigates the advantages of label distribution learning for FER model, by
applying multi-label facial image data to train the model, and measuring the accuracy increase of the multi-label learning scheme compared to the single-label version.

# Tools
- Numpy, Pandas: for data exploration and processing.
- Tensorflow, Keras: for VGG model construction and the implementation of optimization methods.
- Pytorch: for implementation of advanced FER models.
- Dlib: for face detector and ERT-based face alignment model.
- ...

# Database
- [FERPlus](https://github.com/microsoft/FERPlus): the main dataset used in this project for model training and evaluation, which is a collection of approximately 35k facial grayscale images retrieved from another dataset [FER](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data), each annotated by ten taggers into one of ten emotion categories: neutral, happiness, surprise, sadness, anger, disgust, fear, contempt, unknown, not a face.
- [ImageNet](https://www.image-net.org/), [AffectNet](http://mohammadmahoor.com/affectnet/): datasets for model pre-training.
- [SFEW](https://cs.anu.edu.au/few/AFEW.html), [RAF-DB](http://www.whdeng.cn/raf/model1.html): additional training data.

# Models
- VGG: [paper](https://arxiv.org/pdf/1409.1556.pdf), [code](https://github.com/keras-team/keras/blob/v2.10.0/keras/applications/vgg16.py).

- Multi-task EfficientNet-B2: [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9815154), [code](https://github.com/HSE-asavchenko/face-emotion-recognition).

- Distract Attention Network: [paper](https://arxiv.org/pdf/2109.07270v4.pdf), [code](https://github.com/yaoing/dan).

- Region Attention Network: [paper](https://arxiv.org/pdf/1905.04075v2.pdf), [code](https://github.com/kaiwang960112/Challenge-condition-FER-dataset).

# Data Processing
## 

# Relevant Links
- Detailed Report: https://drive.google.com/file/d/1ti-aA3u8cVBTwc1EDlIKhbtv5eitGjOl/view?usp=sharing
- Poster: https://drive.google.com/file/d/14R3P9MfFLjbgcr9hc4kE94a6hSlfW89I/view?usp=sharing
- Presentation Slides:
- Website: https://wp.cs.hku.hk/2021/fyp21022/
