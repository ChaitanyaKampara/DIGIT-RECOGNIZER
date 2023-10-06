# DIGIT-RECOGNIZER
# DATASET 
The MNIST dataset is a well-known and widely used dataset in the machine learning community, particularly for tasks involving image classification. It consists of total 70,000 grayscale images of handwritten digits(dataset), which are 28 pixels by 28 pixels in size and represent a single digit from 0 through 9. The images are divided into a training set of 60,000 images and a test set of 10,000 images. 
# This project will be divided into 3 main parts:

* Working with images in Python.
* Feature Engineering
* Model Prediction and Evaluation

# Working with Images in Python:

In this part of the project, you’ll learn about how both the grayscale and RGB images are represented in the computer. Why RGB images consist of 3 channels and how these 3 channels are used to describe an image similarly why only 1 channel is used to represent a grayscale image. 

The main libraries that we’re going to use is NumPy and for visualization we’ll be using Matplotlib


 

# Feature Engineering:

In this part we will be doing Feature Engineering with respect to images. Now you might be wondering what we mean when we say that we’re going to perform feature engineering with respect to images. Now for images we can create new features by creating new images. This can be done using data augmentation or creating a new image using 1 image just by rotating it or making some changes to it. This helps in increasing models’ robustness and make it more robust against unseen data.

To perform the Feature Engineering, we will be using ImageDataGenerator from keras pre-processing library

 

# Model:

We will be creating a basic KNN Classifier and use it for prediction.Uses proximity to find respective output.
