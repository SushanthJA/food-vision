# Food Vision
This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0.

## 1. Problem
Identifying the type of food given the image of a food-item.

## 2. Data

The images we're working with are from the Food101 dataset (101 different classes of food): https://www.kaggle.com/dansbecker/food-101

The dataset **`food101`** is also available in TensorFlow Datasets: https://www.tensorflow.org/datasets/catalog/food101

## 3. Evaluation

The goal is to beat the DeepFood paper.

They were able to achieve 77.4% top-1 accuracy on Food101 over 2-3 days of training.

So this model needs to score >77.4% accuracy.

## 4. Features

Some information about the data:

* We're dealing with images (unstructured data), so it's probably best we use deep learning/transfer learning.
* There are 101 different types of food (this means there are 101 different classes).
* There are around 75,000+ images with labels in the training set.
* There are around 25,000+ images with labels in the test set.

## 5. Conclusion
We have achieved the goal that we had set out to achieve, i.e, beating the DeepFood paper.

From the results evaluated, we can confirm that our model has outperformed the model built by the authors of DeepFood paper (whose accuracy was 77.4%), with our model scoring an accuracy of 80.08%.

This model can still be improved by better hyper-parameter tuning.
