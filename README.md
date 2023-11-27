## About this Repository:
 This repository contains my contributions towards a project completed on studying neural networks as a method of statistical learning for MATH 4210 Mathematics of Data Science at Georgia Tech over the Spring of 2023. My work dove specifically into Convolutional Neural Networks implemented on a multiclass classification task. Everything posted here is of my own work and all resources, citations, and other various sources are included in the works cited file, presentation slides, and the semi-finished LaTeX compiled PDF file titled "ce_for_clf".

 **[Cross Entropy for Classification](https://github.com/abarton51/cnn-bird-clf/blob/main/notes/ce_for_clf.pdf)**: I wrote a LaTeX document that goes in-depth from start to finish for everything one would need to know about using cross entropy as a loss function for a classication task. I provide intuitive explanations and mathematical proofs all the way from what loss functions are and what entropy is to deriving cross entropy and some of its notable properties.

 **[Presentation Slides](https://github.com/abarton51/cnn-bird-clf/blob/main/presentation_slides_bird_image_clf.pdf)**: The bulk of my work is best summarized in the presentation slides PDF.

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
The task is a classic multiclass classification problem. The target variable is a class probability vector corresponding to the set of classes (bird names) given an input vector corresonding to the image tensor.
