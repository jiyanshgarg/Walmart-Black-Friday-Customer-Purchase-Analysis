# *Walmart Black Friday Customer Purchase Analysis*
Statistical Insights Using Central Limit Theorem & Confidence Intervals

## **Executive Summary**

This project analyzes 550,000+ Walmart Black Friday transactions to understand how customer demographics influence purchase behavior. The analysis applies statistical inference techniques, including the Central Limit Theorem (CLT) and Confidence Interval estimation, to move beyond descriptive statistics and draw population-level business insights from large-scale retail data.

The project demonstrates how data-driven decision-making can be supported using rigorous statistical reasoning rather than intuition or isolated averages.

## **Business Problem**

Retail leaders often ask:

- Do different customer segments actually spend differently?

- Are observed spending differences meaningful at the population level?

- Can marketing and pricing decisions rely on sample-level insights?

Simple averages can be misleading at scale. This project addresses that gap by applying sampling distributions and confidence intervals to evaluate whether demographic differences in spending are statistically significant and business-relevant.

## **Objectives**

The key objectives of this analysis are to:

- Analyze customer purchase behavior across Gender, Age Group, and Marital Status

- Apply the Central Limit Theorem to validate normality of sampling distributions

- Estimate 95% confidence intervals for average purchase amounts

- Determine whether observed differences represent true population differences

- Translate statistical findings into business interpretations

## **Dataset Overview**

- Source: Walmart Black Friday transaction data

- Records: ~550,000 transactions

- Key Variables:
    - User_ID:	User ID
    - Product_ID:	Product ID
    - Gender:	Sex of User
    - Age:	Age in bins
    - Occupation:	Occupation
    - City_Category:	Category of the City (A,B,C)
    - StayInCurrentCityYears:	Number of years stay in current city
    - Marital_Status:	Marital Status
    - ProductCategory:	Product Category 
    - Purchase:	Purchase Amount

The dataset is large enough across all major segments to satisfy CLT assumptions and enable reliable statistical inference.

## **Methodology**

The analysis follows a structured statistical workflow:

- Data validation and exploratory analysis

- Segmentation by demographic variables

- Repeated random sampling to construct sampling distributions

- Application of the Central Limit Theorem

- Construction and interpretation of confidence intervals

- Business-focused inference and conclusions

Care is taken to ensure assumptions are met and results are interpreted correctly at the population level, not just the sample level.

### **Tools & Technologies**

- Python

- Pandas & NumPy for data manipulation

- Matplotlib / Seaborn for visualization
- Scipy for statistical tests

## **Key Insights**

- Differences in average purchase amounts across demographics exist but often overlap statistically

- Large sample sizes reduce uncertainty but do not automatically imply meaningful differences

- Confidence interval overlap indicates that observed gaps may not translate into actionable population-level distinctions

- Statistical inference provides stronger decision support than raw averages alone

## **Business Value**

This project demonstrates how statistical reasoning can:

- Prevent overinterpretation of noisy data

- Support evidence-based retail decisions

- Improve segmentation strategy evaluation

It showcases practical application of probability, statistics, and business analytics on real-world retail data and reflects industry-ready analytical thinking.
