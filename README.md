# Wine Analysis
Wine has been around for a really long time, almost about 5,000 BC. Have we ever thought why it's been around for so long. Because of it is easy to make process of simply yeast eating the natural fermentable sugars in grape juice to give its main product alcohol. Any fruit juice with fermentable sugars can make wine but grapes being higher on the fruit evolutionary ladder on fermentable sugar content we choose grapes for making wine.

<img src="https://i.pinimg.com/originals/f4/9e/a9/f49ea9151a1aa714de4397b5abc10490.gif" width="300" />

# Brief description about the Dataset
Wine Quality dataset is public available for research in the University of California, Irvine Machine Learning repository created by Paulo Cortez (Univ. Minho), Antonio Cerdeira, Fernando Almeida, Telmo Matos and Jose Reis (CVRVV) in 2009. This repository has two datasets of red and white wine samples which consists of inputs includes objective tests (e.g. PH values) and the output is based on sensory data (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).
There are 1599 samples of red wine and 4898 samples of white wine in the data sets. Each wine sample (row) has the following characteristics (columns):

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (score between 0 and 10)

# Data Analysis
- Steps kept in mind while analysing the data:

1st: Import necessary libraries.

2nd: Fetch the dataset from the folder that has been saved into.

3rd: Access the data. For accessing, we may consider looking at the first five rows(head) or last five rows(tail).

4th: Describe and take the information of the data by writing describe and info respectively.

5th: Adding a new column in each dataset and naming as 'Color' which shows whether the wine is 'Red' or 'White'.

6th: Combine 'Red' and 'Wine' dataset for further analysing.

7th: From the column 'Quality', Grouping the Quality numbers into categories of 'Low', 'Medium' and 'High' quality of wines.

# Questions popped up while analysing the Dataset

Q1: Based on histograms of columns in the newly combined dataset, which of the following feature variables appear skewed to the right? Fixed Acidity, Total Sulfur Dioxide, pH, Alcohol?

Answer: Fixed acidity and Alcohol.

Q2: Based on scatterplots of quality against different feature variables, which of the following is most likely to have a positive impact on quality? Volatile Acidity, Residual Sugar, pH, Alcohol?

#Answer: Alcohol.

Q3: Is a certain type of wine (red or white) associated with higher quality?

Answer: The mean quality of red wine is less than that of white wine.

Q4: What level of acidity (pH value) receives the highest average rating?

Answer:High: Lowest 25% of pH values
             Moderately High: 25% - 50% of pH values
             Medium: 50% - 75% of pH values
             Low: 75% - max pH value
'Low level' of acidity recieves highest average rating.

Q5: Do wines with higher alcoholic content receive better ratings?

Answer: Yes, Wines with higher alcoholic content generally receive better ratings.red_wine.

Q6: Do sweeter wines generally receive higher ratings?

Answer: Yes, sweeter wines generally receive higher ratings.

Q7: What level of acidity receives the highest average rating?

Answer: Wines with 'Low' level of acidity recieve highest ratings.

At the end of the analysis, showing a bar chart which shows 'Proportions by Wine Color and Quality'.

# Conclusion of Analysis

According to analysis done above from the data obtained from UCI Machine Learning Repository, it has been found that:

1. The mean quality of red wine is less than that of white wine.
2. Wine with 'Low level' of acidity recieves highest average rating from consumers.
3. Wines with higher alcoholic content generally receive better ratings.
4. Sweeter wines generally receive higher ratings.

# (Please refer to the IPYNB File for detailed analysis).






