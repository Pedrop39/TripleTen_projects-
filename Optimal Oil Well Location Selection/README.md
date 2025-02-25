# Optimal Oil Well Location Selection

## Description

### Introduction
Welcome to the **Optimal Oil Well Location Selection** project! Our mission is to pinpoint the best spot for a new oil well, maximizing profit while keeping risks in check. By analyzing oil well data from three regions, we’ve built a predictive model to estimate reserve volumes, selected the most promising wells, and assessed potential profits and risks using the Bootstrapping technique. The result? A data-driven strategy to guide oil exploration.

### Main Body
This project follows a step-by-step approach to identify the ideal oil well location. Here’s how we did it:

1. **Data Collection and Preparation**  
   - Imported essential libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, and `seaborn`.  
   - Loaded datasets detailing oil well parameters across three distinct regions.  
   - Cleaned the data and conducted exploratory analysis to understand key trends.  
   - Examined feature relationships in each region to inform modeling decisions.  

2. **Model Training and Testing**  
   - Divided data into training and validation sets for each region.  
   - Trained a Linear Regression model per region to predict reserve volumes.  
   - Evaluated model accuracy with Root Mean Squared Error (RMSE) and stored predictions for analysis.  

3. **Profit Calculation**  
   - Set key parameters: total budget, well count, revenue per barrel, and production targets.  
   - Determined the break-even reserve volume and compared it to regional averages.  
   - Built a function to compute profit from selected wells based on model predictions.  

4. **Risk and Profit Analysis**  
   - Applied Bootstrapping to assess profit distributions and risks across regions.  
   - Calculated mean profit, 95% confidence intervals, and loss probabilities for each region.  

### Conclusion
The analysis reveals all three regions as viable options, but Region Two stands out with the highest average profit and lowest risk of loss. Our recommended drilling order is Region Two, followed by Region Three, then Region One—a clear roadmap for maximizing returns.

### Ideas for Further Improvement
- **Feature Enhancement**: Include geological data (e.g., soil composition) for more precise volume estimates.  
- **Real-Time Updates**: Integrate live production data to refine profit and risk forecasts.  
- **Business Impact**: Use insights to prioritize drilling schedules or negotiate better supplier contracts.  
- **Model Upgrade**: Test ensemble models like Random Forest to potentially improve prediction accuracy.  

---

## Getting Started

### Prerequisites
- Python 3.12.3  
- Required libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`  

