# Machine Learning Project: Oil Reserve Prediction and Profit Analysis

## Overview
This project involves using machine learning to predict potential oil reserves in three different regions based on geological data. The primary objective is to determine the most profitable and least risky region for oil drilling using linear regression models.

## Technologies Used
- **Python**: Main programming language.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-Learn**: For implementing linear regression models and performing cross-validation.
- **Matplotlib**: For visualization of results.

## Model Training and Evaluation
The data for each region was split into training and validation sets with a 75/25 ratio. Linear regression models were then trained to predict oil reserves. Model performance was evaluated using Root Mean Squared Error (RMSE), highlighting differences in prediction accuracy among the regions:
- **Region 0**: RMSE of 37.76
- **Region 1**: RMSE of 0.89 (indicating highest accuracy)
- **Region 2**: RMSE of 40.15

## Key Findings
- The RMSE values indicate that Region 1's model is the most accurate, making its predictions the most reliable for further profitability and risk assessments.
- Despite its accuracy, Region 1 predicted lower oil reserves on average, suggesting a need for careful consideration of potential profits versus risks.

## Improvements and Cross-Validation
Feature standardization and cross-validation were used to enhance model reliability:
- Cross-validation results were consistent with initial findings, further supporting the superior performance of the model in Region 1.

## Profit Analysis
A detailed profit analysis was conducted to identify the most economically viable region. This included calculating break-even points and potential profits by selecting the top 200 most promising wells:
- **Region 0** showed the highest potential profit, although with significant risk.
- **Region 1** offered a balance of good profit potential with the lowest risk.
- **Region 2** showed lower profit potential compared to Region 0 but with similar risk levels.

## Bootstrapping for Risk and Profit Estimation
Bootstrapping methods were applied to estimate the profitability and risks associated with each region:
- **Region 1** emerged as the most stable and attractive option, combining lower risk with competitive profit potential, despite having lower raw prediction values for oil reserves.

## Conclusion
The comprehensive analysis suggests that while Region 0 might offer high profits, Region 1 provides a more balanced risk-profit profile, making it the recommended choice for development. Region 2, though not the least profitable, carries risks similar to Region 0 but without the higher profit margins.



