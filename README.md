# Linear Regression Analysis on Ecommerce Data

## Project Overview
Amazon Cloths sells clothing online, where customers visit the store, consult with a personal stylist, and then place orders either through a mobile app or a website. The company aims to determine whether to prioritize improving the mobile app experience or the website based on customer spending behavior.

This analysis explores customer data to identify key factors influencing yearly spending and provides insights into where the company should focus its efforts.

## Data Description
The dataset consists of customer information, including:
- Email, Address, and Avatar (non-numeric attributes)
- Average Session Length
- Time Spent on App
- Time Spent on Website
- Length of Membership
- Yearly Amount Spent (target variable)

## Data Analysis
1. **Exploratory Data Analysis (EDA)**
   - Joint plots were used to analyze the relationships between numerical features and yearly spending.
   - A pair plot was created to identify the most correlated features.
   - A linear model plot was used to examine the relationship between Length of Membership and Yearly Amount Spent.

2. **Feature Selection**
   - Key numerical features were selected, including Average Session Length, Time on App, Time on Website, and Length of Membership.
   - Length of Membership showed the highest correlation with Yearly Amount Spent.

3. **Model Training and Evaluation**
   - The dataset was split into training and testing sets.
   - A linear regression model was trained using the selected features.
   - Model performance was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

4. **Residual Analysis**
   - A histogram of residuals was plotted to confirm normal distribution, ensuring model reliability.

## Key Findings
- Length of Membership had the highest impact on yearly spending.
- Time spent on the mobile app had a stronger correlation with spending compared to time spent on the website.
- The website's impact on spending was minimal, indicating that improving the mobile experience might yield better results.

## Conclusion
Based on the regression analysis, Amazon Cloths should focus on enhancing the mobile app experience as it significantly influences customer spending. Additionally, investing in strategies to increase membership duration could further boost revenue.

