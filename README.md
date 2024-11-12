
# Bank_Campaign_Analysis




## Introduction

The purpose of this analysis is to explore and analyze data related to the launch of a new credit card by AtliQo Bank. The objective is to derive insights that can inform the strategy for the credit card launch and evaluate the impact of the new card on usage and transaction amounts.


## Data Description

The analysis utilizes several datasets, including:

1. Customer Demographics: Contains demographic information about the bank's customers, including age, gender, occupation, and annual income.
2. Transaction Data: Includes details of transactions made by customers using their credit cards, such as transaction amount and date.
3. Product Information: Information about the existing and new credit card products, including features and benefits.
## Data Cleaning

The data cleaning process involved:

1. Handling missing values by imputing them based on the median or mode or as per different category as appropriate.
2. Detecting and treating outliers, particularly in the annual income variable.
Outliers below an income of 100 were replaced with the occupation-wise median income.
3. Ensuring consistency in data formats and types across the datasets.
## Exploratory Data Analysis

### Univariate Analysis

1. Annual Income: Distribution of annual incomes was analyzed. Outliers were treated by replacing values less than 100 with the occupation-wise median income.
2. Age: Age distribution was visualized using histograms and summary statistics.

### Bivariate Analysis

1. Income vs. Occupation: Analyzed the relationship between income levels and different occupations. Found significant income disparity between business owners and other occupations.
2. Income vs. Gender: Explored income differences across genders.
3. Transaction Amount vs. Age: Analyzed how transaction amounts vary with customer age.

### Multivariate Analysis

1. Income, Occupation, and Gender: Visualized the interaction between these three variables to understand the income distribution across different occupations and genders.

## Statistical Tests

### Two Sample Z Test for Hypothesis Testing

#### Hypotheses:

1. Null Hypothesis (H0): The new credit card does not significantly increase the usage or transaction amounts compared to the existing credit card.
2. Alternative Hypothesis (H1): The new credit card significantly increases the usage or transaction amounts compared to the existing credit card.

#### Test Using Rejection Region (Critical Z Value)

The Z score was higher than the critical Z value, leading to the rejection of the null hypothesis.

#### Test Using p-Value

The p-value was less than the significance level (alpha), leading to the rejection of the null hypothesis.

#### Insights:

Using the stats module from statsmodels, a one-tailed Z-test was performed. The results indicated that the new credit card has a statistically significant positive impact on the usage or transaction amounts compared to the existing credit card.

## Conclusion

The exploratory data analysis and statistical tests provided valuable insights:

1. There are noticeable income disparities across different occupations. This information can be pivotal in tailoring marketing strategies for the new credit card.
2. The analysis showed that the new credit card positively impacts transaction amounts and usage, indicating its potential success in the market.
3. The 18-25 age group, which accounts for approximately 26% of the customer base, represents a significant untapped market. This demographic has an average annual income of less than $50k and limited credit history, which affects their credit scores and credit limits. Their usage of credit cards is relatively low compared to other age groups.

