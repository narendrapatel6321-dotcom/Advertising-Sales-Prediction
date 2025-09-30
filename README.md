# MACHINE LEARNING : LINEAR REGRESSION - ADVERTISING SALES PREDICTION

## Project Overview
This project explores the relationship between advertising budgets for TV, radio, and newspaper and their impact on sales using a Linear Regression model. The goal is to identify which advertising channels are most effective in driving sales and provide recommendations based on the findings.

## Dataset
The dataset used in this project contains information on advertising expenditure for TV, radio, and newspaper, along with the corresponding sales figures.
- **Source:** Kaggle (https://www.kaggle.com/sazid28/advertising.csv)
- **Target Variable:** Sales (int) - The resulting sales from the advertisements.
- **Predictors:**
    - TV (int) - Budget allocated for TV advertisements.
    - Radio (int) - Budget allocated for radio advertisements.
    - Newspaper (int) - Budget allocated for newspaper advertisements.

## Methodology
1. **Data Loading and Exploration:** The dataset was loaded and explored to understand its structure, summary statistics, and the correlation between variables.
2. **Exploratory Data Analysis (EDA):** Scatter plots and a correlation heatmap were used to visualize the relationships between the advertising budgets and sales, as well as the relationships between the different advertising channels.
3. **Data Preprocessing:** The data was split into training and testing sets to prepare it for model building.
4. **Model Building and Evaluation:** Linear Regression models were built using different combinations of predictor variables (all predictors, only TV, and TV and Radio). The models were evaluated using metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Cross-Validation Mean.

## Key Findings
- TV advertising showed the highest correlation with sales, followed by Radio. Newspaper advertising had a weaker correlation with sales.
- The Linear Regression model using both TV and Radio as predictors performed best among the models tested, exhibiting the highest R-squared and Cross-Validation Mean, and the lowest error metrics (MAE, MSE, RMSE).

## Conclusion and Recommendation
The analysis suggests that TV and Radio advertisements are more effective in driving sales compared to Newspaper advertisements. Based on these findings, it is recommended to allocate more advertising budget towards TV and Radio channels to maximize sales.

## Libraries Used
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn (model_selection, preprocessing, linear_model, pipeline, metrics)
