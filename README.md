# Loan-Applicant-Credit-Risk-Analysis

**Project Overview**
This project focuses on analyzing loan applicants' financial data to assess their credit risk. The goal is to predict whether an applicant is a high-risk borrower using machine learning models. Key factors such as age, work experience, CIBIL score, and overdraft history play a crucial role in determining creditworthiness.

**Data Exploration & Insights**
**Understanding the Dataset:** We checked the dataset structure, summarized numerical data, and ensured there were no missing values.
**Age Distribution:** Analyzed how different age groups affect loan approval chances.
**Work Experience & City Duration:** Evaluated whether longer work experience and city stability impact creditworthiness.
**CIBIL Score & Cost to Request Ratio:** Key indicators of financial reliability were examined using visualizations.
**Overdrafts & Bounces:** Past financial behavior was analyzed to understand patterns of missed payments.
**Outlier Detection:** Boxplots and violin plots helped identify unusual data points affecting credit risk assessment.
Machine Learning Model Selection
**Data Splitting:** The dataset was divided into training and testing sets for model evaluation.
**K-Nearest Neighbors (KNN):** Tested different values of neighbors to find the best-performing model, achieving an accuracy of 83%.
**Logistic Regression:** A simple and effective model that also achieved 83% accuracy.
**Random Forest Classifier:** Hyperparameter tuning improved accuracy to 84%, making it the best-performing model.
**Hyperparameter Optimization:** Used Randomized Search CV to fine-tune the Random Forest model for better results.

**Conclusion**
Random Forest performed the best with 84% accuracy.
CIBIL score and past overdrafts are strong indicators of loan default risk.
The model provides a data-driven approach for financial institutions to assess creditworthiness before approving loans.
