# Dog Breed Classifier Project
This is repo for the Dog breed classifier project in Udacity's deep learning nanodegree.


# Project Overview:
By providing a set of images in a folder, this can classify whether you have human face, a dog or neither in the image. Also if a dog is detected, it can tell the breed it belongs to, and for humans it shows their most resembling dog breed. This is a unified model with three particular modules.

Module 1 : Human face detector
Module 2 : Dog breed detector
Module 3 : Differentiate between dogs and humans 

# Detecting Humans:
Designing a human face detector using OpenCV, that returns the accuracy of the model using first 100 images of the human face dataset. 

# Classifying Dog Breed:
This uses transfer learning on a pretrained ResNet50 model, which can classify between 133 classes of dog breeds. This detector takes an input image and returns an image with the dog breed label.  
The model is trained to an accuracy of 83%

# Custom CNN model for dog breed classification:
A CNN model made from scratch is used to compare results with a state-of-the-art feature extractor(ResNet50). This model attains an accuracy of 37% on the test dataset.

# Differentiate between Dogs and Humans:
This is the final module that uses both previous models (Human & Dog detector) to detect a dog or a human in the given image. 

# Instructions:
  1. Clone / download_zip this repo. You can .[clone].(git clone https://github.com/aniketrs593/dog_breed_classifier.git) using this link. 
  
  2. Download the human and dog datasets from the given links: 
  [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
  [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

  3. Unzip and place "dog_dataset" at location `dog_breed_classifier/dogImages`.
  4. Unzip and place "human_dataset" at location  `dog_breed_classifier/lfw`
  5. Open a terminal in the repo root folder and type `jupyter notebook`. Open the `dog_app.ipynb` file from the jupyter     notebook directory.
  
