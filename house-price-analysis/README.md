# House Price Analysis and Prediction

## Project Overview
A complete data analysis and machine learning project
that analyzes 1,460 houses from Ames, Iowa to identify
key factors affecting house prices and predict sale prices.

## Dataset
- **Source:** Kaggle House Prices Competition
- **Link:** https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
- **Size:** 1,460 houses, 81 features

## Project Steps
1. Data Collection and Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Missing Value Treatment
4. Data Visualization
5. Machine Learning Model Building
6. Model Comparison and Results

## Key Findings
- Overall Quality is the strongest predictor (0.79 correlation)
- Larger living area means higher price (0.71 correlation)
- Garage size significantly affects price (0.64 correlation)
- Newer houses generally sell for more than older houses
- Most houses are priced between $100,000 and $250,000

## Machine Learning Results
| Model | RMSE | Performance |
|-------|------|-------------|
| Linear Regression | $38,806 | Good |
| Random Forest | $30,029 | Better |
| Winner | Random Forest | Best |

## Charts Created
- Price Distribution
- Correlation Heatmap
- Living Area vs Sale Price Scatter Plot
- Quality vs Price Box Plot
- Year Built vs Price Line Chart
- Model Predictions Chart
- Feature Importance Chart

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Business Recommendations
- Sellers should improve overall quality to increase price
- Buyers should look for older houses with large living areas
- Investors should focus on quality rating 7+ houses
- Builders should prioritize garage and basement space

## How to Run This Project
1. Clone this repository
2. Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
3. Open notebooks/House_Price_Analysis.ipynb
4. Run all cells from top to bottom

## Author
Dushyant
Data Analyst | Python | Machine Learning