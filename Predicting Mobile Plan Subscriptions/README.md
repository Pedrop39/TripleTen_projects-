# Predicting Mobile Plan Subscriptions

## Description

### Introduction
Welcome to the **Predicting Mobile Plan Subscriptions** project! This effort is designed to empower a mobile carrier company by developing a predictive model that analyzes subscribers’ behavior. Our goal? Recommend the perfect plan—either Smart or Ultra—to existing users based on their historical data, helping the company boost engagement and tailor offerings with precision.

### Main Body
This project follows a clear, data-driven path to predict mobile plan subscriptions. Here’s how we brought it to life:

1. **Data Preprocessing**  
   - Imported essential libraries: `pandas`, `numpy`, `sklearn`, and `lightgbm`.  
   - Loaded a dataset rich with subscriber behavior details, from usage patterns to preferences.  
   - Cleaned the data and engineered features to create a solid foundation for modeling.  

2. **Exploratory Data Analysis (EDA)**  
   - Investigated the distribution of features and the target variable (Smart vs. Ultra plans).  
   - Visualized key relationships between subscriber behaviors and plan preferences.  

3. **Model Training and Evaluation**  
   - Tested multiple models: Decision Tree, Random Forest, and Logistic Regression.  
   - Evaluated performance using accuracy, aiming for a minimum threshold of 0.75.  
   - The Random Forest model excelled, achieving an impressive accuracy of 0.8134 on the test set.  

### Conclusion
The Random Forest model emerged as the top performer, delivering an accuracy of 0.8134—well above our target. Its ability to decode subscriber behavior makes it a powerful tool for recommending Smart or Ultra plans, enabling the mobile carrier to personalize offers and enhance customer satisfaction.

### Ideas for Further Improvement
- **Behavioral Insights**: Add features like call duration trends or data usage spikes for richer predictions.  
- **Real-Time Updates**: Integrate the model into a live system to adapt recommendations as habits evolve.  
- **Business Impact**: Use predictions to reduce churn by targeting at-risk subscribers with tailored incentives.  
- **Model Ensemble**: Blend Random Forest with LightGBM for a potential accuracy boost.  

---

## Getting Started

### Prerequisites
- Python 3.12.3  
- Required libraries: `pandas`, `numpy`, `sklearn`, `lightgbm`  

