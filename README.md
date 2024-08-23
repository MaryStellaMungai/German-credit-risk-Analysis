# German Credit Risk Analysis and Prediction

## Description
This project involves analyzing and predicting credit risk using Linear Regression. The goal is to build a model that can predict the creditworthiness of applicants based on their financial and demographic data.

## Files
- `German Credit Risk Analysis and Prediction Using Logistic Regression.ipynb`: Jupyter Notebook containing the analysis and Linear Regression model implementation.
- `german_credit_data.csv`: Dataset used for credit risk prediction.

## Methodology
1. **Data Exploration**: Initial exploration and cleaning of the dataset.
2. **Feature Engineering**: Processing and selecting features for the model.
3. **Model Building**: Building and training a Linear Regression model to predict credit risk.
4. **Evaluation**: Evaluating the model's performance using appropriate metrics.
 ## Data Analysis Questions
1. **What is the correlation between Credit amount and Duration?**
   - **Answer**:Correlation coefficient of 0.62 btwn credit amount and duration indicates
   - -moderately strong +ve relationship implying that higher credit amounts tend to be associated with longer durations &viceversa
      eg borrowers seeking larger credit amounts may opt for longer repayment methods

2. **What is the relationship between savings and risk assessment in the dataset, and why do applicants with substantial savings tend to have lower perceived risk?**
   - **Answer**: -Some people in the dataset have a lot of money saved.
              -Even though they have this money saved up, they are seen as safe borrowers.
                -This suggests that having savings might make lenders feel more comfortable about lending money.
3. **Which applicants have a high credit amount but a short duration for repayment?**
   - **Answer**: People in the dataset are borrowing a lot of money but choosing to pay it back quickly.
   -           -This might mean they want to avoid paying too much interest or they prefer getting rid of debt faster.
   -           -it also suggests they might have limited financial flexibility, needing to pay off the loan quickly, possibly due to urgent needs or financial constraints
4. **Which applicants have a credit amount significantly higher than the average for their job type?**
   - **Answer**: People from various backgrounds are borrowing larger amounts than usual for their jobs.
              -This could signal significant purchases or investments.
               -However, some are considered risky borrowers, suggesting potential repayment challenges.


## Installation
Ensure you have the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

## Usage
1. Open `German Credit Risk Analysis and Prediction Using Logistic Regression.ipynb` in Jupyter Notebook.
2. Run the cells to perform the data analysis and see the model's predictions.
 ## Data Insights
 -Applicants with substantial savings tend to be perceived as lower risk, but exceptions exist.
-High credit amounts are often associated with longer repayment durations.
-Some applicants borrow large amounts relative to their job type, which could indicate significant purchases or financial strain.
-The logistic regression model shows decent predictive power, with an accuracy of 71%.
 
