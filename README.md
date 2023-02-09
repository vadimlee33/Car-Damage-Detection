# Car Damage Detection Project

This project aimed to develop a deep learning model for detecting damage on cars.
The model was trained on a dataset of images of cars, which was divided into damaged and whole cars.

## Requirements
- Python (3.8.13)
- TensorFlow (2.10.0)
- Scikit-learn (1.0.2)
- KerasTuner (1.0.3)
- Numpy (1.22.3)
- OpenCV (4.5.5)

## Data
The data for this project was a collection of images of cars, which was divided into whole and damaged samples.
The data was split into a training set and a validation set.

## Models
The model was a Convolutional Neural Network (CNN) implemented in TensorFlow.
The architecture of the network was determined through experimentation and hyperparameter tuning.
Also, we implemented Transfer Learning to get better results.
Transfer Learning Models: VGG16 and DenseNet121

## Evaluation
The performance of the model was evaluated using metrics such as precision, recall, and F1 score. The model was tested on a validation set of images that were not seen during training.
