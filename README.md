# Airbnb Seattle Dataset Analysis

## Overview
This project focuses on analyzing the Airbnb Seattle dataset to uncover factors that influence nightly listing prices. Various machine learning techniques, such as feature correlation analysis, principal component analysis (PCA), and Lasso regression, were used to identify important features affecting the price.

## Objective
To determine the factors most correlated with predicting the listing nightly price in Seattle Airbnb listings.

## Project Structure

### 1. Data Preprocessing
- **Dataset**: Airbnb Seattle Dataset
- **Cleaning**: Handle missing values, normalize and scale features.
- **One-Hot Encoding**: Applied to categorical variables to prepare for further analysis, resulting in a large number of columns.
- **Outlier Detection**: Detect and remove outliers to ensure model performance.

### 2. Feature Analysis
- **Correlation Analysis**: Investigated which features are most correlated with the listing price using Pearson correlation.
- **VIF Calculation**: Performed Variance Inflation Factor (VIF) analysis to handle multicollinearity and removed features with high VIF.
- **PCA**: Principal Component Analysis was used to reduce dimensionality, given the large number of features post-encoding.

### 3. Model Building
- **Lasso Regression**: Applied to identify the most significant features affecting listing prices. The regularization helped deal with the high-dimensional feature space, resulting in a simpler, interpretable model.
- **Coefficient Analysis**: Features with the highest impact were extracted and visualized.

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
   git clone https://github.com/your-username/airbnb-seattle-analysis.git

Navigate to the project directory:
bash
Copy code
cd airbnb-seattle-analysis
Install the necessary packages:
bash
Copy code
pip install -r requirements.txt
Open the Jupyter notebook:
bash
Copy code
jupyter notebook airbnb-seattle-analysis.ipynb
Results
Key results and visualizations from the analysis are included in the notebook. A summary of the most influential features affecting Airbnb listing prices in Seattle is provided through the Lasso Regression analysis.

Author
Your Name - LinkedIn - GitHub

yaml
Copy code

---

This structure will render well as a Markdown file for your project.



