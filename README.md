# NaiveBayes_Breast_Cancer_Dataset

This is a Python code for implementing Naive Bayes classification on the Breast Cancer Dataset. The dataset comprises features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features include measures such as mean radius, mean texture, and mean smoothness, along with the diagnosis indicating whether the breast mass is benign or malignant. 

The code is divided into two parts: Gaussian Naive Bayes and Categorical Naive Bayes.

**Gaussian Naive Bayes**
The Gaussian Naive Bayes implementation assumes that the likelihood of the features given the class label follows a Gaussian distribution. It preprocesses the data, calculates priors and likelihoods, and then predicts the class label for test data. Evaluation metrics such as accuracy, precision, recall, F1 score, ROC curve, AUC, and log loss are calculated and visualized.

**Categorical Naive Bayes**
The Categorical Naive Bayes implementation is tailored for categorical features. It discretizes the continuous features into categories, calculates priors and likelihoods, and predicts the class label for test data. Similarly, evaluation metrics such as accuracy, precision, recall, F1 score, ROC curve, AUC, and log loss are calculated and visualized.

These questions has been answered:

e.1 How can I measure the performance of my model?
e.2 What are: Accuracy, Confusion Matrix, Precision, Recall & F1 Score, ROC & AUC. Log Loss?
