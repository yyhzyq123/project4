
# Data Scientist Capstone

This `Data Scientist` capstone project explores the field of `Artifitial Intelligence`. Here, I would like to build a `Computer Vision` pipeline that can be used within a web or mobile app to process real-world, user-supplied images. In this project, given an image of a dog, the algorithm will identify and estimate the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. My project blogpost can be found [here](https://github.com/yyhzyq123/project4/blob/master/bolg.md).

## Dog Breed Classifier

Use `Convolutional Neural Networks` to Identify Dog Breeds.

The coding details of the project are at: [jupyter notebook.](https://github.com/yyhzyq123/project4/blob/master/dog_app.ipynb)

### 1) Project Motivation

### 2) Libraries Used

The following python libraries were used in this project

* opencv-python==3.2.0.6
* h5py==2.6.0
* matplotlib==2.0.0
* numpy==1.12.0
* scipu==0.18.1
* tqdm==4.11.2
* keras==2.0.2
* skikit-learn==0.18.1
* pillow==4.0.0

### 3) Datasets Used

- Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo at location `path/to/dog-project/dog_images`. 

- Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo at location `path/to/dog-project/lfw`.  

- Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset. Place it in the repo at location `path/to/dog-project/bottleneck_features`.

- Donwload the [DogResnet50Data.npz](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz). Place it in the `bottleneck_features` folder in the repository.

### 4) File Descriptions

* dog_app.ipynb:coded file
* image：Blog Image Folder
* image_dog:Test image folder
* saved_models:Model save file
* bolg.md:Blog files

### 5) Results Analysis

* Basic implementation of recognition function and successful testing

### Acknowledgements

I would like to thank [Udacity](https://learn.udacity.com/nanodegrees/nd025) for providing great online learning resources and being part of my academic journey!

