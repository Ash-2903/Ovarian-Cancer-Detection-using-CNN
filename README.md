# Ovarian-Cancer-Detection-using-CNN

The code consists of python implementation of a Convolutional Neural Network (CNN) model built using TensorFlow and Keras libraries. The purpose of this file is to classify images into two classes, with a focus on binary classification. The classes are - Ovarian Cancer and Ovarian non-Cancer.

Training and Validation Accuracy Graph:
The training and validation accuracies stabilize and fluctuates between 0.9 to 1.0. The training accuracy is maintaining a high level. The validation accuracy is also high and closely follows the training accuracy. Hence, there is no significant overfitting.

Training and Validation Loss Graph:
The training loss decreases from the start and hence the model is minimizing the error on the training data. The validation loss also decreases but shows more fluctuations than the training loss.

![image](https://github.com/user-attachments/assets/d3e03f46-d5d2-44a9-8bea-aaf30c3673bc)

Confusion Matrix :
True Positives (TP): 497 (correctly predicted as Ovarian Non-Cancer)
True Negatives (TN): 464 (correctly predicted as Ovarian Cancer)
False Positives (FP): 17 (incorrectly predicted as Ovarian Cancer but they were Ovarian Non-Cancer)
False Negatives (FN): 9 (incorrectly predicted as Ovarian Non-Cancer but they were Ovarian Cancer)
![WhatsApp Image 2024-09-17 at 20 55 14_60848ecf](https://github.com/user-attachments/assets/85cf06c8-0288-4b9f-a4e4-fd14616fd523)

Overall Performance:
Accuracy: 97%
Macro Avg: Averages the precision, recall, and F1-score across both classes equally. Each class has a precision, recall, and F1-score of 0.97.
Weighted Avg: Takes into account the support (number of instances) of each class to compute the average. Still results in 0.97 across precision, recall, and F1-score.
![image](https://github.com/user-attachments/assets/166dacd6-94be-495a-b097-9cd9c7dd6c62)

