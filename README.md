Retail Customer Churn Prediction using Machine Learning
Overview
This project is an end-to-end machine learning solution designed to predict customer churn in a retail business environment using synthetic customer behavioral data. The project simulates real-world retail analytics by generating customer purchase patterns, performing exploratory data analysis (EDA), engineering meaningful business features, training a Random Forest classification model, and evaluating predictive performance using industry-standard metrics. The objective is to identify customers who are likely to stop purchasing from the business so companies can take proactive retention measures.
Features
Synthetic retail customer dataset generation
Exploratory Data Analysis (EDA)
Customer churn prediction using Random Forest Classifier
Feature engineering using Customer Lifetime Value (CLV)
Model evaluation using ROC-AUC, Classification Report, and Confusion Matrix
Business-oriented visualizations and insights
Feature importance analysis to identify key churn drivers
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Dataset Features
The generated dataset contains the following attributes:
Feature
Description
CustomerID
Unique customer identifier
Recency_Days
Days since last purchase
Frequency_Purchases
Total purchases made
Avg_Spend_USD
Average spending per order
Tenure_Days
Customer relationship duration
Total_CLV
Estimated customer lifetime value
Churned
Target variable (1 = churned, 0 = active)
Machine Learning Workflow
Generate realistic retail customer data
Perform exploratory data analysis
Engineer business-focused features
Split data into training and testing sets
Train Random Forest classification model
Evaluate model performance
Visualize customer churn insights and feature importance
Evaluation Metrics
The model is evaluated using:
ROC-AUC Score
Precision
Recall
F1-Score
Confusion Matrix
Visualizations Included
Recency vs Customer Churn
Feature Importance Analysis
Confusion Matrix Heatmap
Project Goal
The main goal of this project is to demonstrate how machine learning can help retail businesses predict customer churn, improve customer retention strategies, and make data-driven business decisions.
How to Run the Project
Bash
# Clone the repository
git clone <your-repository-link>

# Navigate to the project folder
cd retail-customer-churn-prediction

# Install required libraries
pip install numpy pandas matplotlib seaborn scikit-learn

# Run the Python file
python churn_prediction.py
Future Improvements
Use real-world retail datasets
Deploy model using Flask or Streamlit
Add hyperparameter tuning
Compare multiple ML algorithms
Build interactive dashboards
Author
Pratham Kumar
License
This project is open-source and available for educational and learning purposes.
