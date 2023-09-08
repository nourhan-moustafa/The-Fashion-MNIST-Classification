# The-Fashion-MNIST-Classification
Image Classification using Convolutional Neural Networks (CNN) - LeNet vs. AlexNet

In this project, we explore the application of Convolutional Neural Networks (CNN) for image classification using two well-known algorithms: LeNet and AlexNet. The primary objective is to investigate these algorithms, provide a simplified explanation of their architecture, and critically compare their performance using the Fashion MNIST dataset.

Overview:

This notebook implements a CNN-based image classification system, specifically designed to process images and categorize them into predefined classes. It consists of a series of convolutional and pooling layers followed by fully-connected (dense) layers.

Key Components:

TensorFlow Version Specification: The notebook specifies the TensorFlow version as 2.x, ensuring compatibility.

TensorBoard Integration: TensorBoard, a tool for visualizing training progress and debugging TensorFlow models, is loaded as an extension.

Importing Relevant Modules: Necessary libraries, including TensorFlow, NumPy, Matplotlib, and Seaborn, are imported.

GPU Availability Check: The code checks for the presence of a GPU for TensorFlow 2.x and raises an error if not found.

Selected Dataset: The Fashion MNIST dataset is loaded and its shape is printed for inspection.

Data Preprocessing: The training and test data are normalized and reshaped to fit the algorithm.

Algorithm No.1: LeNet:

A LeNet-5 model is defined, which consists of convolutional and dense layers.
The model is compiled with the Adam optimizer and categorical cross-entropy loss.
Training and evaluation of the LeNet model are performed, and results are displayed.
TensorBoard is deployed to visualize training progress.
Algorithm No.2: AlexNet:

An AlexNet-inspired model is defined with convolutional and dense layers.
The model is compiled with the Adam optimizer and categorical cross-entropy loss.
Training and evaluation of the AlexNet model are performed, and results are displayed.
TensorBoard is deployed for visualizing training progress.
Boosting the CNN Classifier with Data Augmentation:

Data augmentation techniques, such as horizontal/vertical flipping, rotation, and shifting, are applied to improve model robustness.
The performance of the augmented model is compared with the original model.
Relative Performance of CPU and GPU:

The notebook measures and compares the performance of a convolutional operation on both CPU and GPU, highlighting the potential speedup gained by using GPU acceleration.
This notebook serves as a comprehensive guide for implementing and comparing CNN-based image classification algorithms on the Fashion MNIST dataset, enabling you to gain insights into the world of deep learning and model evaluation.
