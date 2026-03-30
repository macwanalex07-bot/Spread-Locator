
# Spread Locator – Statistical Distribution Analysis Model
## Project Overview
This project analyzes e-commerce transaction data using statistical distributions and probability analysis.

The objective is to understand purchasing behavior, analyze spread of transaction amounts, and determine which probability distributions best fit the dataset.

## Project Structure

Part A – Theoretical Foundation  
Explains statistical distribution concepts including:
- Q-Q Plot
- Bernoulli Distribution
- Binomial Distribution
- Poisson Distribution
- Log-Normal Distribution
- Power Law Distribution
- Box-Cox Transformation
- Z-score Probability
- PDF vs CDF

Part B – Data Analysis
Implemented using Python libraries:
- NumPy
- Pandas
- SciPy
- Matplotlib
- Seaborn
- Statsmodels

## Steps Performed
1. Load and explore dataset
2. Fit Binomial distribution for success/failure transactions
3. Fit Poisson distribution for transactions per day
4. Model transaction amounts using Log-Normal distribution
5. Generate Q-Q plot for normality testing
6. Apply Box-Cox transformation
7. Compute Z-scores for anomaly detection
8. Plot PDF and CDF for transaction amounts

## How to Run

1. Install required libraries

pip install pandas numpy matplotlib seaborn scipy statsmodels

2. Open Jupyter Notebook

jupyter notebook

3. Run the notebook

PartB_Distribution_Analysis.ipynb

## Outcome
The project identifies the best statistical distributions for modeling transaction data and provides insights useful for decision-making in an e-commerce platform.
