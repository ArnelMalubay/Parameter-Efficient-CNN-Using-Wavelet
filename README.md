# Parameter-Efficient Convolutional Neural Networks Using Wavelet Transforms
This repository contains the notebooks and other files that I used in the completion of my thesis project entitled Parameter-Efficient Convolutional Neural Networks Using Wavelet Transforms. The abstract for this thesis, which is shown below, was accepted in the 3rd International Conference on Applied & Industrial Mathematics and Statistics 2022. Training was done on Google Colab. I personally accomplished all of the programming aspect of this project, and was thereby assigned to be its corresponding author. The paper itself was made in collaboration with my thesis partner, Kurt de los Santos and my thesis adviser, Dr. Job Nable.
# Abstract
Convolutional Neural Networks (CNN's) are known to perform well on computer vision tasks such as image classification, image segmentation, and object detection. However, one major drawback of CNN's is the huge amount of computing and memory resources needed to train them. In this paper, we propose an architectural unit which we call Upsampling-Based Wavelet Residual Block (UBWRB), that utilizes the 2D discrete wavelet transform coupled with upsampling operators and a residual connection to extract features from image data while having relatively fewer trainable parameters as compared to traditional convolutional layers. The discrete wavelet transform is a family of transforms that find extensive applications in signal processing and time-frequency analysis. For this paper, we use the filter-bank implementation of the discrete wavelet transform, allowing it to act in a similar fashion to a convolutional layer with fixed kernel weights. We demonstrate the performance and parameter-efficiency of CNN's with UBWRB's in the task of image classification by training them on the MNIST, Fashion-MNIST, and CIFAR-10 datasets. Our best-performing models achieve a test accuracy of 99.32\% on the MNIST dataset while having less than 120,000 trainable parameters, and 92.78\% and 83.55\% on the Fashion-MNIST and CIFAR-10 datasets respectively, with both having less than 180,000 trainable parameters. 
