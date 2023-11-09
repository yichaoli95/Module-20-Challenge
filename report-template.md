# Module 20 Report 

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

*  The aim of this study was to construct machine learning models for anticipating the risk of loan default using financial data. The objective was to establish models capable of discerning between sound loans (class 0) and high-risk loans (class 1), with the intent of assisting financial institutions in making well-informed lending decisions.
* The dataset utilized in the analysis encompassed diverse financial parameters associated with loans. The primary aim was to anticipate the probability of a loan being categorized as high-risk, indicating a potential default. Such predictions hold significance for financial institutions in effectively mitigating risks linked to lending.
* The target variable for prediction was the "loan_status" column, with 0 denoting a healthy loan and 1 signifying a high-risk loan. The distribution of these labels was evident in the dataset's "value_counts."
* The analysis progressed through the following stages:

1. Data Loading and Splitting: The dataset was imported into a Pandas DataFrame and subsequently divided into training and testing sets.
2. Model Generation: A logistic regression model was formulated using the training data.
3. Model Assessment: The model's effectiveness was assessed through metrics like accuracy, precision, recall, and F1-score.
4. Interpretation and Comparison: The model's outcomes were interpreted, and a comparative analysis was conducted in relation to the business problem's specifications.
* The predominant methodology employed in this analysis centered on logistic regression, a commonly utilized classification algorithm tailored for binary prediction tasks. Its application was geared towards forecasting the probability of a loan being classified as high-risk, relying on the provided features.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model：Logistic Regression

Training Set Performance: Accuracy: 99% Precision for 0: 100% Precision for 1: 86% Recall for 0: 99% Recall for 1: 90%

Testing Set Performance: Accuracy: 99% Precision for 0: 100% Precision for 1: 86% Recall for 0: 100% Recall for 1: 91%

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
*The logistic regression model excelled in forecasting the risk of loan defaults, demonstrating impressive accuracy, precision, and recall for both "0" and "1" labels across both training and testing sets. These outcomes affirm the model's efficacy in distinguishing between healthy and high-risk loans.

*In the context of predicting loan defaults, precision and recall for the "1" label (high-risk loans) hold particular significance. The logistic regression model attains noteworthy values in these metrics, underscoring its capability to accurately identify high-risk loans while maintaining a high level of precision.

*Given these results, the logistic regression model emerges as the most favorable choice, achieving a commendable equilibrium between accurately identifying high-risk loans and minimizing false positives. Nevertheless, a more comprehensive analysis, incorporating business requirements and the potential ramifications of false positives and false negatives, should be undertaken before finalizing the model selection.
