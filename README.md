# Airbnb Seattle Dataset Analysis


## Overview

This project analyzes the Airbnb Seattle dataset to uncover trends and factors that influence nightly listing prices. By leveraging data science techniques like feature correlation, outlier detection, and **Lasso Regression**, we extract meaningful insights that could benefit both Airbnb hosts and travelers.

### Why this matters?
Understanding what drives Airbnb listing prices in Seattle can help hosts optimize their offerings and travelers make smarter booking decisions. From seasonal trends to neighborhood hotspots, this analysis digs into the data to bring actionable insights.

## Research Questions

This analysis focuses on answering the following questions:

1. **What months witnessed the peak of the average listing nightly price in Seattle?**
2. **What are the top 3 neighborhood groups in terms of average nightly price in Seattle?**
3. **What factors are most correlated with predicting the listing nightly price?**

## Dataset
- **Source**: [Airbnb Seattle Dataset on Kaggle](https://www.kaggle.com/datasets/airbnb/seattle)
- **License**: [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)


## Project Structure

### 1. Data Preprocessing
- **Dataset**: The Airbnb Seattle dataset.
- **Data Cleaning**: Handled missing values and performed normalization/scaling of features.
- **One-Hot Encoding**: Applied to categorical variables, resulting in a large number of columns.
- **Outlier Detection**: Detected and removed outliers to improve model performance.

### 2. Feature Analysis
- **Correlation Analysis**: Investigated which features are most correlated with listing prices using Pearson correlation.
- **VIF Calculation**: Performed Variance Inflation Factor (VIF) analysis to handle multicollinearity, removing features with high VIF values.

### 3. Model Building
- **Lasso Regression**: Applied to identify the most significant features affecting listing prices. This technique handled the high-dimensional feature space and helped simplify the model.
- **Coefficient Analysis**: Extracted and visualized the features with the highest impact.

### 4. Consolidating Categorical Features
- Aggregated one-hot encoded features (e.g., amenities, room types) to simplify feature interpretation.

### 5. Results
- **Key Findings**: Presented through coefficient values and visualizations, identifying top factors influencing price.

## Files

- **airbnb-seattle-analysis.ipynb**: The Jupyter notebook containing the entire analysis.
- **visualizations**: Folder containing graphs showing feature importance, correlation heatmaps, and regression coefficients.

## Instructions to Run

1. Clone the repository:
   ```bash
  git clone https://github.com/mohanadelemary/airbnb-seattle-analysis.git
  cd airbnb-seattle-analysis
  pip install -r requirements.txt
  jupyter notebook airbnb-seattle-analysis.ipynb

## Results
Key results and visualizations from the analysis are included in the notebook. A summary of the most influential features affecting Airbnb listing prices in Seattle is provided through the Lasso Regression analysis.

Author
Mohanad Elemeary
GitHub Profile https://github.com/mohanadelemary

License
This project uses the Airbnb Seattle Dataset, which is licensed under CC0: Public Domain.


