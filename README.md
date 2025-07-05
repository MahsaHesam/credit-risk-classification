


![What-is-credit-risk](https://github.com/user-attachments/assets/bcb425e4-7861-4306-988a-5c21d078c5a9)






**Overview of the Analysis**

I've analysed financial data including loan size, interest rate, borrower income, debt-to-income ratio, account count, credit delinquencies, and total debt.I have used LogisticRegression. The goal was to classify loans as either healthy (0) or high-risk (1).

**Steps:**

Data Split
Initial Model
Model Evaluation


**Results**
The model accuracy is 0.99 which means it can accurately classify nearly all (99%) of the loans.

Healthy loans: The model is excellent at identifying good loans (100% precision) with almost no mistakes (very few false positives). It also catches nearly all healthy loans (100% recall) with very few missed.
High-risk loans: The model is good at recognizing risky loans (87% precision), although there might be some misclassifications (some false positives). However, it's still effective in finding most high-risk loans (89% recall) with just a few missed.
In simpler terms, the model is great at spotting both good and bad loans, with a slightly higher success rate for healthy loans.

**Summary**
Based on the results and analysis the logistic regression model works very well with precision for both 0 (healthy loan) and 1 (high-risk loan)
