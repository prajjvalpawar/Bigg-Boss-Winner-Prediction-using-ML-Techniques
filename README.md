## Bigg Boss Winner Prediction Using Machine Learning

This project is a complete Bigg Boss winner prediction system using historical contestant data and a Random Forest-based machine learning model. It predicts the most likely winner of a season and ranks contestants based on winning probability, helping analyze patterns behind victories.

### Problem
Predicting the winner of Bigg Boss is challenging because many factors influence the outcome: contestant performance, popularity, captaincy, number of evictions, and social media presence. Manually analyzing these factors is time-consuming, error-prone, and subjective.

### Solution
This project provides an automated solution:  
- The Random Forest model analyzes historical data and predicts the winner with probability scores.  
- Contestants are ranked based on their likelihood of winning.  
- This approach provides data-driven insights and helps understand which factors impact winning chances.

### Features
- Prediction of winners for completed seasons based on historical data  
- Probability-based ranking of contestants  
- Future season winner prediction using sample data  
- Easy-to-understand ML pipeline for real-world entertainment data

### Working
- Random Forest Classifier is used because it handles non-linear relationships, reduces overfitting, and works well with structured data.  
- Features like age, captaincy, performance metrics, social media popularity, and evictions faced are used for prediction.  
- The model predicts winning probability instead of just a binary outcome, allowing ranking of contestants.  
- Future season predictions are made by creating sample contestant data and feeding it into the trained model.

### Dataset
The dataset contains historical Bigg Boss contestant data from previous seasons, including features like:  
- Age  
- Number of times elected as captain  
- Number of evictions faced  
- Performance metrics (best/worst performer)  
- Social media popularity

### Key Learnings
- Feature engineering improves model accuracy  
- Probability-based predictions give better insights than binary labels  
- Random Forest is effective for tabular datasets

### Future Enhancements
- Incorporate more social media metrics and public voting trends  
- Build a Streamlit app for an interactive winner prediction demo  
- Experiment with advanced models like XGBoost for better accuracy

### How to Use
1. Open the notebook `BiggBoss_Winner_Prediction.ipynb` in Google Colab.  
2. Run the cells step by step to train the model and see predictions.  
3. For future season prediction, create sample contestant data and run the prediction cells.

Created by: **Prajjval Pawar | B.tec CSE, 2026**
