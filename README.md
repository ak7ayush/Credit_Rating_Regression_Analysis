# ***Overview***

---


- The objective of the model was to predict the Credit Rating of a customer
- To achieve this objective a Linear Regression Model was built
- `Limit` and `Balance` were the predictor features in the final Model

# **Coefficients and Significance**

---


- The coefficient of predictor variable `Limit` is positive (0.0658), indicating an increase in Income associated with with a higher predicted Credit Rating. This coefficient is statistically significant (p-value < 0.05), suggesting a strong relationship.

- For each additional unit increase in Income, the predicted credit rating is expected to increase by 0.0658 points

- The coefficient of predictor variable `Balance` is positive (0.0056), indicating an increase in Credit Limit associated with with a higher predicted Credit Rating. This coefficient is statistically significant (p-value < 0.05), suggesting a strong relationship.

- For each additional unit increase in Limit, the predicted credit rating is expected to increase by 0.0056 points

- Credit Rating will be affected more by Credit Limit than Balance. It is not to say that Balance is not an important feature in predicting Credit Rating.


# **Model Performance**

---

- <u>Metric Scores</u>
    - *Mean Squared Error (MSE):* 118.75
    - *Root Mean Squared Error (RMSE):* 10.89
    - *Mean Absolute Error (MAE):* 9.025
    - *R-squared (R2):* 0.99
    - *Adjusted R-squared (Adj R2):* 0.99
    
    
- **The scores indicate high accuracy of the model with good performance on prediction**


# **Insights**

---

- Higher Credit Limits are positively correlated with higher credit ratings. Individuals with higher credit limits tend to have better credit ratings.

- The Balance variable doesn't appear to have a significant impact on credit ratings, as its coefficient is close to zero and not statistically significant.


# ***Recommendations:***

---

- Financial institutions may consider offering higher credit limits to customers who meet specific creditworthiness criteria, as this could potentially lead to improved credit ratings.

- While Balance does not seem to have a significant impact on credit ratings in this model, it's still important for customers to manage their balances responsibly to maintain good credit standing.
- Optimal Credit Utilization: Encourage borrowers to maintain a healthy credit utilization ratio by responsibly using their available credit. This can positively impact their credit ratings. Provide educational materials on how to manage credit limits effectively to avoid overutilization.

- Credit Counseling: Offer credit counseling services to individuals with high balances and low credit ratings. Providing guidance on debt reduction strategies and budgeting can help them improve their credit scores over time.

- Credit Limit Reviews: Periodically review and adjust credit limits for existing customers based on their creditworthiness and financial behavior. Responsible credit utilization can contribute to a positive credit rating.


## **Model Limitations**

---

- The model may not capture all factors that influence credit ratings, such as payment history and employment status. Further analysis and additional variables could enhance the predictive power.

- The linear regression assumption of linearity may not hold perfectly for the relationship between predictors and credit ratings. Exploring other modeling techniques like polynomial regression could be considered.