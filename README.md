#### About this Repository:
 This repository contains my contributions towards a project completed on studying neural networks as a method of statistical learning for MATH 4210 Mathematics of Data Science at Georgia Tech over the Spring of 2023. My work dove specifically into Convolutional Neural Networks implemented on a multiclass classification task. Everything posted here is of my own work and all resources, citations, and other various sources are included in the works cited file, presentation slides, and the unfinished LaTeX compiled PDF file titled "math4803neuralnetworks".
 
 In addition to keeping record of my project contributions, I am currently working on converting my local implementation to a Kaggle submission. I'm not sure how much I will change it but I will likely stick to fewer models and possibly add the pretrained EfficientNetB0 model due to the poor performance I found using the ImageNet pretrained ResNet50 on the full 515 bird species dataset. Lastly, the Kaggle submission will likely be implemented only on the most recently updated data, which is currently at 525 bird species as of May 5th, 2023, and I won't be doing model and data exploration on a subset of data as I did for my project.

# Bird Image Classification Task with Convolutional Neural Networks

## The Dataset:
The datset consists of colored images of birds. Each image is at least of size 224 x 224 with RGB channels stored as JPG or PNG file.\
The dataset is taken from https://www.kaggle.com/datasets/gpiosenka/100-bird-species?resource=download

### Full Dataset:
515 Bird Species

87,874 images split as follows:\
  Training - 82,724\
  Validation - 2,575 (5 images per species)\
  Test - 2,575 (5 images per species)

### Subset of Dataset:
100 Bird Species

16,824 images split as follows:\
  Training - 15,824\
  Validation - 500\
  Test - 500

## The Task
The task is a classic multiclass classification problem. The target variable is a deterministic class probability vector corresponding to the set of classes (bird names) given an input vector corresonding to the image tensor.
