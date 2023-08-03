# Home Credit Analysis

## Table of contents
- [Summary of the Business problem and Project Objective](#Summary-of-the-Business-problem-and-Project-objective)
- [Solution to the Business Problem](#Solution-to-the-Business-Problem)
- [Contribution to the Project](#Contribution-to-the-Project)
- [Difficulties that group encountered along the way](#Difficulties-that-group-encountered-along-the-way)
- [The business value of the solution](#The-business-value-of-the-solution)
- [Learnings from this project](#Learnings-from-this-project)


## Summary of the Business Problem and Project Objective

Home Credit is facing a significant challenge in accurately assessing the repayment capabilities of prospective borrowers with limited or no credit history. This leads to the risks of approving loans for individuals likely to default and rejecting applicants who can actually repay. To address this issue, Home Credit is seeking an advanced analytics solution that utilizes its data to improve the prediction of clients' repayment abilities. By implementing this solution, Home Credit aims to reduce financial losses, make informed loan approval decisions, and promote financial inclusion for the unbanked population. The project will focus on building a predictive model using alternative data and supervised learning techniques to achieve its objectives. The success of the project will be measured based on the accuracy of repayment predictions, reduction in loan defaults, increased loan approvals, and overall improvement in Home Credit's financial performance.
The goal of the Home Credit Default Risk project is to develop predictive models that can accurately assess the likelihood of clients defaulting on their loan payments. By leveraging various data points and features, the project aims to provide insights to the lending institution for better credit risk assessment and decision-making.

## Solution to the Business Problem

We selected Extreme Gradient Boosting (XGBoost) as our model of choice due to its initial lower accuracy score (89%) compared to other models. However, XGBoost offered more advanced parameters and features, making it an attractive candidate for further investigation. To address data imbalance, we employed the Synthetic Minority Oversampling TEchnique (SMOTE), leading to improved accuracy scores and more favorable metrics like the AUC Precision-Recall curve.
Our analysis identified credit scores as highly correlated with default risk, making them crucial in the final analysis. We also noticed a substantial number of missing values in the dataset, prompting consideration of removing records with over 60% missing data unless they prove useful later. Visualizations indicated a preference for smaller cash-dominant loans, and we observed that individuals seeking higher loans also had a greater number of outstanding loans to manage. The data join process generated numerous new records, necessitating a reevaluation. 

## Contribution to the project

In the project during the EDA phase, I took charge of visualizing the data to gain insights and identify patterns. Additionally, I played a crucial role in data cleaning, ensuring that the dataset was prepared for modeling with accurate and reliable information. In the modeling phase, I worked on implementing both the logistic regression model and the XGBoost model. While the logistic regression encountered some challenges and produced suboptimal results due to errors, I persisted and found success with the XGBoost model, which yielded better outcomes. Moreover, I actively participated in creating the project notebook, providing well-organized and documented analysis and findings. My efforts contributed to the successful implementation of the XGBoost model and the generation of valuable insights from the data, helping the team make informed decisions and achieve positive outcomes for the project.

## Difficulties that group encountered along the way

One of the primary difficulties was related to data preprocessing and cleaning. The dataset we worked with had numerous missing values and inconsistencies that required careful handling to ensure the accuracy of our analyses. Additionally, we faced difficulties in selecting the appropriate machine learning models for the task at hand. We experimented with various models, including logistic regression, which encountered errors and did not produce satisfactory results. It took significant effort and iterations to settle on the XGBoost model, which ultimately proved to be effective in providing better predictions.

## The business value of the solution
The proposed solution using Extreme Gradient Boosting (XGBoost) with Synthetic Minority Oversampling TEchnique (SMOTE) holds significant business value for our organization. By leveraging XGBoost's advanced features and parameters, we aim to achieve improved accuracy in predicting default risks, thus minimizing potential losses from risky loans and enhancing overall portfolio performance. The implementation of SMOTE addresses data imbalance, ensuring a more comprehensive analysis and reliable predictions. The focus on credit scores as a key factor in the analysis will enable better risk assessment and decision-making when approving loans. Furthermore, the solution's data cleaning and normalization processes will enhance data quality and promote more informed insights. Overall, this solution promises to enhance our loan approval process, optimize loan portfolios, and ultimately lead to better financial outcomes, reducing default rates, and increasing overall profitability for the organization.

## Learnings from this project

Throughout the project, I gained valuable knowledge and skills that have significantly enriched my understanding of data analysis. Working on the exploratory data analysis (EDA) phase allowed me to discover the importance of visualizations in uncovering patterns and trends within the data. I also learned the significance of data preprocessing and cleaning to ensure the reliability of our models. The challenges we faced during model selection and implementation taught me the importance of experimenting with different models to find the most suitable one for a given problem. Overall, this project has been a valuable learning experience that has equipped me with practical skills and insights.


