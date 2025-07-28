💳 Credit Scoring System
This project focuses on building a Credit Scoring System using a logistic regression model to predict whether a client will default on their credit payment in the next month. It includes data preprocessing, model training, evaluation, and performance reporting.

📌 Project Overview
The goal of this project is to predict credit default risks using customer demographic and financial information. The project uses a cleaned dataset with manually mapped categorical features and applies machine learning to classify clients as defaulters (1) or non-defaulters (0).

📄 Repository Contents
File/Folder	Description
CREDIT SCORING SYSTEM.ipynb	Jupyter Notebook containing code for preprocessing, modeling, and evaluation
Credit Scoring System 1.docx	Project overview with data exploration, preprocessing steps, and modeling details
Model Evaluation Report.docx	Detailed model performance report with classification metrics and improvement suggestions
README.md	Project documentation (this file)

🧪 Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib)

Jupyter Notebook

Logistic Regression for classification

⚙️ Key Steps
Data Exploration

Verified absence of null values

Confirmed no duplicates using ID column

Validated categorical columns for uniqueness

Preprocessing

Manual mapping of categorical values

Feature scaling applied (excluding ID and target column)

Modeling

Used Logistic Regression for training

Dataset split into training and test sets

Evaluation

Accuracy: 81%

Precision (class 0): 0.82, Precision (class 1): 0.69

Recall (class 1): 0.24 – indicating low detection of defaulters

F1 Score (class 1): 0.35

Identified significant class imbalance

📈 Performance Insights
The model performs well on the majority class (non-defaulters) but poorly on the minority class (defaulters).

Imbalance in the dataset results in low recall for class 1.

Adjusting the decision threshold or applying resampling techniques like SMOTE could improve performance.

🧠 Recommendations
Adjust Decision Threshold to increase sensitivity for defaulters.

Use Class Weights in the model to penalize errors on the minority class more heavily.

Explore other models:

Random Forest

XGBoost (handles class imbalance better)

✅ Conclusion
This project demonstrates a practical approach to credit risk modeling. While initial results are promising, especially for non-defaulters, improvements are needed for better detection of high-risk clients. Addressing class imbalance is a key next step.

# Credit-Scoring-System
