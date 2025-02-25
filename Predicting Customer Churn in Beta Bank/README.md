# Predicting Customer Churn in Beta Bank

## Description

### Introduction
Welcome to the **Predicting Customer Churn in Beta Bank** project! Our mission is to develop a predictive model that pinpoints customers at risk of leaving Beta Bank. By leveraging historical data on client behavior and contract terminations, we aim to equip the bank with actionable insights to retain its customer base and strengthen loyalty.

### Main Body
This project follows a structured, data-driven approach to predict customer churn. Here’s how we made it happen:

1. **Data Exploration and Preprocessing**  
   - Imported key libraries: `pandas`, `numpy`, `sklearn`, and `matplotlib`.  
   - Loaded a dataset filled with customer details, from demographics to account activity.  
   - Filled missing values with median estimates for robustness.  
   - Standardized categorical features by converting them to lowercase.  
   - Verified the dataset was free of duplicates.  

2. **Exploratory Data Analysis (EDA)**  
   - Examined the distribution of features and the target variable (churn status).  
   - Explored relationships between features like Credit Score, Age, and churn likelihood.  
   - Analyzed correlations among numerical features to uncover key drivers.  

3. **Data Preprocessing**  
   - Applied one-hot encoding to categorical variables like Geography and Gender.  
   - Split the data into training, validation, and test sets for reliable evaluation.  
   - Balanced the class distribution using upsampling and downsampling to address churn rarity.  

4. **Model Training and Evaluation**  
   - Tested Decision Tree, Random Forest, and Logistic Regression models.  
   - Evaluated performance with F1-score and AUC-ROC metrics to capture precision and recall.  
   - The Random Forest model led the pack, achieving an F1-score of 0.60 on the test set post-upsampling.  

### Conclusion
The Random Forest model delivered the strongest results, hitting an F1-score of 0.60 on the test set. Its ability to identify at-risk customers makes it a vital tool for Beta Bank, enabling proactive retention strategies to keep clients from walking away.

### Ideas for Further Improvement
- **Feature Expansion**: Incorporate behavioral signals like transaction frequency or customer service interactions.  
- **Real-Time Alerts**: Integrate the model into a dashboard to flag churn risks instantly.  
- **Business Impact**: Pair predictions with personalized offers to reduce churn rates and lift revenue.  
- **Advanced Balancing**: Experiment with SMOTE or ensemble methods to further enhance F1 performance.  

---

## Getting Started

### Prerequisites
- Python 3.12.3  
- Required libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`  

