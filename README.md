# FraudDetection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent transactions using a supervised machine learning approach. Fraudulent activity poses significant challenges to financial systems, and early detection helps prevent massive financial losses.Using Python and machine learning libraries, this project builds a logistic regression model to classify transactions as legitimate or fraudulent based on key features extracted from a given dataset.

## Usage
1.Launch Jupyter Notebook.

2.Open FraudeDetection.ipynb

3.Run each cell sequentially to:

    i) Load and preprocess data.

    ii) Train the logistic regression model.

    iii) Evaluate model performance.

    iv) Visualize results.
    
## Methodology
1.Data Preprocessing:

    -Handled class imbalance using SMOTE Technique.


2.Model Training:

        -Used Logistic Regression from scikit-learn.

        -Trained on features selected from the dataset.

        -Split data into training and testing sets.

3.Performance Evaluation:

    -Accuracy

    -Precision

    -Recall

    -F1-score


## Result

| Metric    | Score           |
| --------- | --------------- |
| Accuracy  | 0.97            |
| Precision | 0.97            |
| Recall    | 0.98            |
| F1-Score  | 0.97            |


## Conclusion

This project demonstrates the use of logistic regression for fraud detection, a critical task in financial sectors. The model performed well with high accuracy and balanced precision-recall, making it reliable for detecting fraudulent activities. While logistic regression is interpretable and efficient, further enhancements could be made using more complex models such as Random Forests, XGBoost, or neural networks, especially in cases of severe class imbalance or nonlinear relationships.

