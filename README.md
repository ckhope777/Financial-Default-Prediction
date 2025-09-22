![Python](https://img.shields.io/badge/Python-3.9-blue.svg)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange.svg)  

# Financial-Default-Prediction
Project focuses on default prediction and financial analysis to assess a company’s ability to meet its debt obligations. Using machine learning models, financial ratios, and feature importance analysis, the project identifies key drivers of default risk and builds a predictive framework to classify companies as likely to default or not.

## Workflow & Steps ##

1. **Problem Understanding**  
   - Defined the task as binary classification: *Default* vs *Non-Default*.

2. **Data Preparation**  
   - Cleaned missing values & standardized financial ratios.  
   - Engineered new predictors such as debt-to-equity, current ratio, and profit margins.

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of financial ratios.  
   - Correlation analysis to check feature relevance.  

4. **Model Building**  
   - Trained Logistic Regression, Decision Tree, and Random Forest.  
   - Hyperparameter tuning for Random Forest to maximize predictive power.  

5. **Model Evaluation**  
   - Compared models using accuracy, precision, recall, and F1-score.  
   - Random Forest outperformed with highest stability.  

6. **Feature Importance Analysis**  
   - Identified leverage, liquidity, and profitability ratios as key predictors.  

7. **Final Conclusion**  
   - Random Forest selected as the production-ready model.  
   - Provides a robust framework for **early warning system in credit risk assessment**.
  
## Final Results ##
- **Best Model:** Random Forest Classifier  
- **Performance Metrics:**  
  - Accuracy: ~0.88  
  - Macro Avg F1 Score: ~0.73  
  - Weighted Avg F1 Score: ~0.89  
- **Key Predictors:** leverage ratios, liquidity ratios, profitability margins

## Tech Stack ##
- **Programming Language:** Python (pandas, NumPy, matplotlib, seaborn, scikit-learn)  
- **Environment:** Jupyter Notebook → Exported as HTML for documentation  
- **Models Used:** Logistic Regression, Decision Tree, Random Forest  
- **Visualization:** Correlation plots, feature importance graphs, model performance metrics  
