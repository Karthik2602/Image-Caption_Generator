# Image-Caption-Generator
Project

In this project, we use CNN and LSTM to identify the caption of the image. 
As the deep learning techniques are growing, huge datasets and computer power are helpful to make models that can generate captions for an image.
This is what we’re going to apply in this Python based project where we will be using deep learning techniques like CNN and RNN.
Image caption generator is a process which involves natural language processing and computer vision concepts to recognize the context of an image and present it in English. 
In this project, we carefully follow some of the core concepts of image captioning and its common approaches.
We discuss Keras library, numpy and Kaggle notebook for the making of this project. 
We also discuss about flickr_dataset and CNN used for image classification.


SYSTEM ARCHITECTURE

The proposed model of Image Caption Generator is as shown in the above figure. Here in this model, input image is given & then A convolutional neural network is used to create a dense feature vector as shown in figure. This dense vector, also called an embedding, this vector can be used as input into other algorithms, and it generates suitable caption for given image as output. For an image caption generator, this embedding becomes a representation of the image and used as the initial state of the LSTM for generating meaningful captions, for the image.

![image](https://user-images.githubusercontent.com/118602686/204021666-cf0a2f83-e9a5-43c0-ac17-53cd389cb793.png)

DATASETS

1. Flickr8k_Dataset – Dataset folder which contains 8091 images.
2. Flickr_8k_text – Dataset folder which contains text files and captions of images.
