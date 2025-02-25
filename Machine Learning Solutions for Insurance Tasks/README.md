# Machine Learning Solutions for Insurance Tasks

## Description

### Introduction
Welcome to the **Machine Learning Solutions for Insurance Tasks** project! The Sure Tomorrow insurance company is harnessing machine learning to tackle key challenges. Our goal? Evaluate and deliver solutions for four tasks: finding similar customers for marketing, predicting insurance benefit likelihood, estimating benefit counts with linear regression, and safeguarding client data through obfuscation—all while maintaining model performance.

### Main Body
This project tackles the four tasks through a structured, data-driven approach. Here’s how we did it:

1. **Data Preprocessing & Exploration**  
   - Imported core libraries: `numpy`, `pandas`, `seaborn`, and `sklearn`.  
   - Loaded the dataset and verified its integrity with basic checks.  
   - Standardized column names and adjusted data types for consistency.  
   - Conducted exploratory data analysis (EDA) to map out data structure and distributions.  

2. **Task 1: Similar Customers**  
   - Created a k-nearest neighbors (kNN) function to identify similar customers using Euclidean and Manhattan distances.  
   - Tested with and without `MaxAbsScaler` to assess scaling’s impact on kNN results.  
   - Compared outcomes across distance metrics to optimize neighbor selection.  

3. **Task 2: Predicting Insurance Benefit**  
   - Framed the task as binary classification to predict benefit receipt.  
   - Built a kNN classifier and measured its F1 score across various k values.  
   - Benchmarked it against a dummy model with random probability predictions.  

4. **Task 3: Regression with Linear Regression**  
   - Developed a linear regression model to estimate the number of insurance benefits.  
   - Coded a custom implementation and evaluated it with RMSE and R² metrics.  
   - Tested performance on both original and scaled data for robustness.  

5. **Task 4: Data Obfuscation**  
   - Designed a transformation algorithm, multiplying features by an invertible matrix to mask personal data.  
   - Confirmed the matrix’s invertibility and demonstrated data recovery.  
   - Proved—analytically and empirically—that obfuscation preserves linear regression accuracy.  

### Conclusion
This project showcases machine learning’s power for insurance tasks. Scaling boosts kNN performance for customer similarity, the kNN classifier outshines a dummy model for benefit prediction, linear regression holds steady across data types, and our obfuscation method protects privacy without sacrificing results. Sure Tomorrow now has a solid toolkit to enhance operations.

### Ideas for Further Improvement
- **Advanced Clustering**: Use DBSCAN or hierarchical clustering for more nuanced customer segmentation.  
- **Real-Time Predictions**: Deploy models in a live system for instant benefit assessments.  
- **Business Impact**: Leverage predictions for targeted marketing or risk-based pricing strategies.  
- **Enhanced Privacy**: Explore differential privacy techniques to further secure client data.  

---

## Getting Started

### Prerequisites
- Python 3.12.3  
- Required libraries: `numpy`, `pandas`, `seaborn`, `sklearn`  

