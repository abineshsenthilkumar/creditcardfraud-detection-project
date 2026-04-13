# creditcardfraud-detection-project
Overview:
This project is about detecting fraudulent credit card transactions using machine learning. The main challenge here is that fraud cases are very rare compared to normal transactions, which makes the problem more interesting and closer to real-world scenarios.

Problem

Banks and financial platforms face losses due to fraud transactions. The goal of this project is to build a model that can identify such fraud cases as accurately as possible.

Dataset
Total records: 284,807
Fraud cases: 492
Highly imbalanced dataset

The features are already transformed (PCA), so we don’t have actual column meanings.

What I Did
1. Data Understanding
Checked dataset structure and missing values
Observed class imbalance
2. Data Analysis
Visualized fraud vs normal transactions
Compared transaction amounts
Looked at time distribution
Used correlation heatmap to understand feature relationships
3. Model Building
Used Logistic Regression
Handled imbalance using class_weight='balanced'
Split data into training and testing
4. Evaluation

Instead of depending only on accuracy, I focused on:

Precision
Recall
F1-score
ROC-AUC
Key Learnings
Accuracy is not reliable for imbalanced datasets
Recall is very important in fraud detection (to avoid missing fraud cases)
Simple models can still perform well if handled properly
Output

The model is able to identify fraud transactions reasonably well considering the imbalance in the dataset.

How to Run
Open the notebook in Google Colab or Jupyter
Upload the dataset (creditcard.csv)
Run all the cells
Future Improvements
Try advanced models like Random Forest or XGBoost
Build a small dashboard for real-time predictions
Improve feature engineering
Final Note

This project helped me understand how machine learning works in real-world problems, especially when dealing with imbalanced data.
