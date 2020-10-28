# AnalyzeABTesting
## AB Testing Analysis
### Data Files
1. ab_data.csv
2. countries.csv

## Project Description
For this project, I will be working to understand the results of an A/B test run by an e-commerce website. The goal is to utilize practical statistics, regression, and other data analysis tools to help the company determine if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Part I - Probability
1. Load data into dataframe and clean
2. Obtain basic proportions for statistics such as (but not limited to):
  a. conversion rate regardless of treatment or control
  b. probability an individual received the treatment page
  c. conversion rate of individual who received control page

## Part II - A/B Test
1. Assume under the null hypothesis,  𝑝𝑛𝑒𝑤  and  𝑝𝑜𝑙𝑑  both have "true" success rates equal to the converted success rate regardless of page - that is  𝑝𝑛𝑒𝑤  and  𝑝𝑜𝑙𝑑  are equal
2. Use 5% Type I error rate
3. Create sample to perform sampling distribution to show differences in conversion
4. Compare results of hypothesis test with statsmodels.api z-test.

## Part III - Regression Approach
1. Fit a regression model to see if there is a significant difference in conversion based on which page a customer receives.
2. Find p-value and determine if value support the null hypothesis or rejects the null in support of the alternative hypothesis.
3. Add additional data, e.g. country data, to see if any impact is made on results.
4. Are there any influeces associated with time on conversion?
