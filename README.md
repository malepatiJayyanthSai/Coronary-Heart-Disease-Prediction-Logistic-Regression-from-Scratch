# Coronary-Heart-Disease-Prediction-Logistic-Regression-from-Scratch
This project presents a fully custom implementation of logistic regression designed to predict the 10-year risk of coronary heart disease. No libraries were used for model fitting — every component was built from the ground up using Python and NumPy.

1.Manual Implementation of Sigmoid Function Built the core probability estimator 1 / (1 + e^(-z)) from scratch.

2.Custom Loss Function with L2 Regularization Developed binary cross-entropy with regularization to prevent overfitting.

3.Gradient Calculation Computed partial derivatives for each weight and bias manually, incorporating regularization into the gradient flow.

4.Gradient Descent Loop Designed a training loop that:

       4.1 Tracks total loss across iterations

       4.2 Updates weights and bias using learning rate

       4.3 Halts on convergence (loss change < tolerance)

5.Feature Engineering :

       5.1 Z-score normalization applied to continuous features

       5.2 Removed correlated attributes (diaBP, currentSmoker) to reduce multicollinearity
6.Model Evaluation :
       Achieved 85.77% accuracy on test data 
       
7.Tech Used:

    1. Python 3
    2. Numpy
    3. Pandas
    4. Matplotlib & Seaborn (for data and loss visualization)
    5. Sklearn for train,test splitting and accuracy score, confusion matrix

8.DataSet Overview:

The dataset originates from the Framingham Heart Study, a long-term cardiovascular research project on residents of Framingham, Massachusetts. It is publicly available on Kaggle and contains over 4,000 patient records and 15 attributes, each representing potential risk factors associated with coronary heart disease (CHD).

The primary goal is to predict the 10-year risk of developing CHD using patient information, making it a binary classification problem.
