# Predicting Customer Churn for Telecom Operator Interconnect

## Description

### Introduction
Welcome to the **Predicting Customer Churn for Telecom Operator Interconnect** project! Our goal is to craft a predictive model that spots customers likely to churn from Telecom Operator Interconnect. By diving into historical data on client behavior and contract terminations, we aim to arm the telecom operator with insights to proactively retain its subscribers and safeguard its customer base.

### Main Body
This project unfolds through a meticulous, data-driven process to predict customer churn. Here’s how we achieved it:

1. **Data Exploration and Preprocessing**  
   - Imported essential libraries: `pandas`, `numpy`, `sklearn`, `seaborn`, `matplotlib`, and `imblearn`.  
   - Loaded and merged datasets covering customer details, contracts, internet, and phone services into a unified DataFrame.  
   - Filled missing service-related values with 'No' to reflect their absence.  
   - Standardized column names, replaced inconsistent values, and converted dates to `datetime` format (using placeholders for missing dates).  
   - Transformed financial columns to numeric types, addressing any missing entries.  

2. **Exploratory Data Analysis (EDA)**  
   - Studied the distribution of monthly charges and churn rates across contract types (notably higher for month-to-month).  
   - Investigated internet service usage (DSL, fiber optic, or none) and payment method trends (e.g., elevated churn with electronic checks).  
   - Calculated customer tenure before churn, highlighting a prevalence of short-term subscribers.  
   - Explored links between payment methods and monthly charges to uncover retention clues.  

3. **Feature Engineering**  
   - Applied one-hot encoding to categorical variables for model readiness.  
   - Defined the churn target variable while excluding columns prone to data leakage.  

4. **Model Training and Evaluation**  
   - Split data into training and test sets, balancing classes with SMOTE in the training set.  
   - Tested Logistic Regression, Random Forest, and Gradient Boosting models with grid search for hyperparameter tuning.  
   - Evaluated performance using AUC-ROC and accuracy metrics.  
   - The Random Forest model excelled, achieving an AUC-ROC of 0.827 and accuracy of 0.782 on the test set.  
   - Validated results with Stratified K-Fold Cross-Validation, yielding mean AUC-ROC of 0.834 and accuracy of 0.795.  

### Conclusion
The Random Forest model stood out as the top performer, boasting an AUC-ROC of 0.827 and accuracy of 0.782 on the test set. Its robust predictions make it a game-changer for Telecom Operator Interconnect, offering a reliable way to identify and retain at-risk customers with confidence.

### Ideas for Further Improvement
- **Behavioral Features**: Add usage patterns (e.g., call frequency, data consumption) for deeper insights.  
- **Live Monitoring**: Embed the model in a real-time system to flag churn risks as they emerge.  
- **Business Impact**: Pair predictions with loyalty incentives to slash churn rates and boost revenue.  
- **Model Refinement**: Explore CatBoost or XGBoost to push AUC-ROC and accuracy even higher.  

---

## Getting Started

### Prerequisites
- Python 3.12.3  
- Required libraries: `pandas`, `numpy`, `sklearn`, `seaborn`, `matplotlib`, `imblearn`  

