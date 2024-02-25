# LR_Optimizers

This project focuses on logistic regression with different optimizers. It explores the performance of various optimization algorithms in logistic regression using the MNIST dataset.

## Table of Contents

1. [Importing Libraries](#importing-libraries)
2. [Loading MNIST Dataset](#loading-mnist-dataset)
3. [Subsetting The Data to The Classes 0 and 1](#subsetting-the-data-to-the-classes-0-and-1)
4. [Visualizing Some of The Data](#visualizing-some-of-the-data)
5. [Training Logistic Regression Models](#training-logistic-regression-models)

## 1. Importing Libraries <a name="importing-libraries"></a>

This section covers the necessary libraries imported for the project, including numpy, pandas, matplotlib, keras, tensorflow, and sklearn.

## 2. Loading MNIST Dataset <a name="loading-mnist-dataset"></a>

Here, the MNIST dataset is loaded using the `mnist.load_data()` function from Keras. The dataset is divided into training and validation sets.

## 3. Subsetting The Data to The Classes 0 and 1 <a name="subsetting-the-data-to-the-classes-0-and-1"></a>

This section focuses on subsetting the data to include only classes 0 and 1. The indices of the samples belonging to these classes are stored, and the data is concatenated accordingly.

## 4. Visualizing Some of The Data <a name="visualizing-some-of-the-data"></a>

This section provides visualizations of some samples from the dataset, showcasing the images of digits 0 and 1.

## 5. Training Logistic Regression Models <a name="training-logistic-regression-models"></a>

logistic regression models are trained using different optimizers. The models are trained on the subsetted data of classes 0 and 1.
