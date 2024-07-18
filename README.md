# Image-Classification
Introduction
In this project, our goal was to enhance the accuracy of a Convolutional Neural Network (CNN) for classifying images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 color images in 10 different classes, with 6,000 images per class. This dataset is a standard benchmark for evaluating the performance of deep learning models in image classification tasks.

Methods Used
To achieve better accuracy, we implemented several techniques including Data Augmentation, Batch Normalization, Dropout, and Learning Rate Scheduler.

Data Augmentation:

Data Augmentation helps in creating variations in the training dataset, thereby improving the model's generalization.
This was implemented using the ImageDataGenerator in Keras, which included transformations such as rotation, shifting, shearing, zooming, and horizontal flipping.
Batch Normalization:

Batch Normalization accelerates training and improves model stability by normalizing the inputs of each layer.
Dropout:

Dropout is a regularization technique that prevents overfitting by randomly dropping neurons during training.
Learning Rate Scheduler:

The Learning Rate Scheduler automatically adjusts the learning rate during training, helping the model converge more efficiently.
Results

