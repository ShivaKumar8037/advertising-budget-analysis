# Linear Regression Analysis on Advertising Budgets

## Overview

In this project, I delved deep into the world of linear regression, exploring the intricacies of how advertising budgets across various media channels impact sales. Using R as the primary tool for analysis, I examined a dataset that captures the essence of sales and advertising dynamics across different markets.

### Dataset

The dataset, `Advertising.csv`, encapsulates sales data (in thousands of units) for a product across 200 distinct markets. Alongside, it details the advertising budgets (in thousands of dollars) allocated for the product over three media channels: TV, radio, and newspaper.

## Analyses Conducted

### Data Loading and Visualization
I began by loading the data into R, followed by a comprehensive summary and visualization of the dataset to get a grasp of its structure and patterns.

### Simple Linear Regression
I assessed the relationship between sales and the advertising budgets across each medium. The coefficients' interpretation provided insights into how each advertising medium contributed to sales.

### Multiple Linear Regression
I further conducted a multiple linear regression analysis, incorporating the variables TV, Radio, and Newspaper as regressors. By calculating the R-squared, I could derive the efficacy and relevance of each regressor. A 3D visualization of the model was created using the `scatter3d(Sales~TV+Radio)` function from the `car` library.

### Models with Interaction Terms
Exploring potential synergies between advertising media was crucial. I experimented with multiple regression models that integrated interaction terms, especially focusing on the interplay between TV and Radio.

### Sales Optimization
To provide actionable insights, I strategized the allocation of a USD 300K advertising budget, emphasizing the channels TV and Radio. Through forecasting, I compared optimal sales figures with the actual sales in the dataset. Additionally, a confidence interval was computed to ascertain the reliability of the sales prediction.
