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
By applying these techniques, we were able to significantly improve the model's accuracy. Our initial model had an accuracy of around 76%, but with the applied techniques, we achieved an accuracy of approximately 85%. This improvement demonstrates the positive impact of these optimization techniques on the model's performance.

Conclusion
In this project, we successfully enhanced the accuracy of a CNN for CIFAR-10 image classification using Data Augmentation, Batch Normalization, Dropout, and Learning Rate Scheduler. While more complex models like ResNet or DenseNet can achieve higher accuracies, our goal was to show the effectiveness of these straightforward optimization techniques on a basic model.

Implementation and Achievements
Through implementing these techniques and using CIFAR-10 training data, we achieved an accuracy of around 85%. This achievement highlights the success of improving model performance with simple and effective optimization methods.

Future Work
For future work, more complex models and deeper networks can be explored to achieve even higher accuracies. Advanced techniques like Neural Architecture Search and more sophisticated tuning methods can also be considered.
