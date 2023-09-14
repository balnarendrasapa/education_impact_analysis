# Education Level and Performance Analysis

## Background 📚:
This project 📊 analyzes a dataset 📂 containing records of individuals with varying levels of education 🎓, ranging from Less than High School to Graduate, alongside their performance scores 📈. The dataset categorizes people into five different education groups.

## Purpose 🎯:
Our objective 🤔 is to determine whether there is a significant difference in the scores among individuals with different education levels 📝. We aim to answer whether education level has a meaningful impact on a person's performance 🧠. We conducted an analysis 📈 to identify if there is a statistically significant difference in scores among these education groups, ruling out randomness 🎲.

## Methods 📊:
We employed Analysis of Variance (ANOVA) 📊 to compare the means of each education group. This choice was made because we have more than two groups, making the T-Test or Z-Test unsuitable without increasing the type-1 error rate 📉. Our analysis began with Exploratory Data Analysis (EDA) 📊 to prepare the dataset for ANOVA. We formulated hypotheses 📜 for ANOVA, with the null hypothesis stating that there is no difference among the means of the groups and the alternative hypothesis suggesting that at least one group has a different mean.

## Results 📈:
Our analysis yielded a p-value lower than the significance level 📏, and the F-Statistic exceeded the F-Critical value 📊. Consequently, we rejected the null hypothesis in favor of the alternative hypothesis 📉.

## Conclusion 📝:
Based on substantial evidence 📊, we conclude that there is indeed a significant difference among the means of education groups 📚, and this difference is not due to randomness 🎲. Specifically, we found that two pairs of groups have significantly different means: 1) "Less than High School" - "Graduate" and 2) "Less than High School" - "Bachelor's". Therefore, we can assert that individuals who have completed their Graduate or Bachelor's education 🎓 have different scores compared to those who did not pass High School 🏫.

For a more detailed analysis and results, please visit this [website](https://balnarendrasapa.github.io/education_impact_analysis/docs/intro). 🌐
