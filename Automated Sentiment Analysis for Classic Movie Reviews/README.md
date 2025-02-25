# Automated Sentiment Analysis for Classic Movie Reviews

## Description

### Introduction
Welcome to the **Automated Sentiment Analysis for Classic Movie Reviews** project! The Film Junky Union, a vibrant community of classic movie enthusiasts, tasked us with building a system to filter and categorize movie reviews. Our objective? Train a model to automatically detect negative reviews with precision, targeting an F1 score of at least 0.85. Using a labeled IMDB movie reviews dataset, we’ve crafted a solution to distinguish between positive and negative sentiments—perfect for movie buffs who want to cut through the noise.

### Main Body
This project brings sentiment analysis to life through a structured, data-driven approach. Here’s how we did it:

1. **Data Loading and Initialization**  
   - Imported key libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `nltk`, `spacy`, and `lightgbm`.  
   - Loaded the IMDB movie reviews dataset with polarity labels (positive/negative).  

2. **Exploratory Data Analysis (EDA)**  
   - Investigated review trends over time and the distribution of review lengths.  
   - Visualized sentiment balance with bar charts.  
   - Generated correlation heatmaps to uncover relationships between numerical features.  

3. **Data Preprocessing**  
   - Cleaned the text: converted to lowercase, stripped digits and punctuation.  
   - Split data into training (80%) and testing (20%) sets.  
   - Transformed text into numerical features using `TfidfVectorizer` for model compatibility.  

4. **Model Training and Evaluation**  
   - Tested multiple models: Dummy Classifier (baseline), Logistic Regression, and LightGBM.  
   - Evaluated performance with accuracy, precision, recall, and F1-score.  
   - LightGBM emerged as the champion, achieving an accuracy of 0.87 and an F1-score exceeding 0.85.  

### Conclusion
The LightGBM model delivered stellar results, surpassing the target F1 score of 0.85. By effectively handling class imbalance and leveraging text features, it’s a robust tool for classifying movie reviews. This system empowers the Film Junky Union to spotlight negative feedback instantly—a win for community curation!

### Ideas for Further Improvement
- **Enhanced Features**: Incorporate word embeddings (e.g., BERT) for deeper semantic understanding.  
- **Real-Time Deployment**: Integrate the model into a web app for live review analysis.  
- **Business Impact**: Offer sentiment insights to studios or streaming platforms for targeted marketing.  
- **Multiclass Expansion**: Extend the model to detect neutral reviews or specific emotions (e.g., joy, anger).  

---

## Getting Started

### Prerequisites
- Python 3.12.3  
- Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `nltk`, `spacy`, `lightgbm`  



