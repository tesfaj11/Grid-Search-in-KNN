# Grid-Search-in-KNN
Project Conclusion: K-Nearest Neighbors with Grid Search
In this project, we applied the K-Nearest Neighbors (KNN) algorithm and used Grid Search to determine the optimal value for k—the number of neighbors considered when classifying data points. The goal was to build a classification model that predicts whether a patient is diabetic based on features such as glucose level, insulin, BMI, and others.

What We Did:
Used GridSearchCV to test values of k ranging from 1 to 30.

Identified the best-performing value of k as 23, with a cross-validation accuracy of 76%.

Evaluated the model on the test dataset, which achieved an accuracy of 75%.

What We Learned:
The model performed well at predicting non-diabetic cases (class 0), with a recall of 87%.

It was less effective at identifying diabetic cases (class 1), with a recall of 55%, meaning nearly half of the actual diabetic cases were missed.

This indicates a potential issue with class imbalance or insufficient sensitivity to the minority class.

Key Takeaway:
Although the model achieved acceptable overall accuracy, its ability to detect diabetic cases was limited. In real-world healthcare applications, this could be problematic, as identifying positive cases (diabetics) is critical. To improve the model, further steps could include:

Exploring alternative models such as logistic regression or random forests.

Addressing class imbalance through oversampling techniques or advanced methods like SMOTE.

Adding or engineering new features to improve predictive power.
