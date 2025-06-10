# SyriaTel Customer Churning Analysis
**Author**: [Clement Wanderi](mailto:clement.wanderi@student.moringaschool.com)
## Overview
In business, "churn" refers to the rate at which customers stop doing business with a company over a specific period. It's often expressed as a percentage of the total customer base and indicates how well a business is retaining its customers. High churn rates can signal potential problems with customer satisfaction, product quality, or customer service.
## Business Understanding
The churn rate is the percentage of customers who stop using a service or product within a specific timeframe. Churn rate is a crucial metric for businesses, particularly those with recurring revenue models like subscriptions or contracts. It helps businesses understand how well they are retaining customers and can indicate areas where improvements are needed.

This model aims to answer a few objectives such as:

- What is the current churning rate according to the available dataset?
- Can we be able to see the factors that affect the churning rates most?
- Can we be able to predict the churning rate of the company in the time to come?
- What is the accuracy of the prediction model that is created?
From this project we will be aiming to be able to evaluate the current churning rate from the dataset that is available. From this evaluation, we can then be able to predict future instances of customer churning and analyze the accuracy of the model.
## Data
This project utilizes data from the Churn in Telecom dataset from Kaggle. The target variable in this dataset that we aimed to predict was the churn column. The features of this dataset include locational information as well as plan details such as call minutes, charges, customer services calls and whether the customer had an international plan and/or voice mail plan. 
## Methods
This project utilizes:
- Logistic regression
- Decision trees
- Identifying class imbalance
- SMOTE method
- Feature importance and optimization
- Hyperparameter tuning
## Results
The following factors are the most prominent in accidents; having a single engine, a reciprocating engine type, traveling for personal purposes, as well as being in the landing phase of flight.
![Value Counts](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/value_counts.png)
The most common aircraft make involved in accidents is the Cessna.
![Aircraft Make Frequency](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/top_10_most_common_makes.png)
The data has a single peak in July with this having the highest number of recorded aircraft accidents.
![Number of Accidents by Month](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/images/number_of_accidents_by_month.png)
## Conclusions
From the analysis and prediction models above we can come to the conclusion that:

- High churn is linked to service dissatisfaction, particularly among international users and those who frequently contact customer service.
- Proactive engagement with high-usage customers and those with frequent support calls may help reduce churn.
- Predictive models can flag potential churners with >93% accuracy using only 16 key features.
## Recommendations
Operational Strategy:
- Create churn risk scores from the model and integrate into CRM systems.
- Focus retention efforts on customers flagged by the model.

Customer Support:
- Investigate customers with high support calls—improve issue resolution processes.

Marketing & Offers:
- Offer tailored incentives to customers with international plans or high usage.

Model Deployment:
- Consider periodic retraining with fresh data.
- Monitor model drift and feature shifts over time.
## Next Steps
Further analyses that could yield additional insights to further improve the churning model are:

- Apply ensemble models (Random Forest, XGBoost) for potentially better performance.
- Try SHAP or LIME for explainable AI insights.
- Consider customer lifetime value alongside churn prediction for better ROI targeting.
## For More Information
See the full analysis in the [Jupyter Notebook]([aviation_company_risk_analysis.ipynb](https://github.com/CWanderi/P3-Project/blob/main/SyriaTel_Customer_Churn_Analysis.ipynb)) or review this [presentation](https://github.com/CWanderi/Clement_Project_Phase_1/blob/main/Aviation%20Company%20Risk%20Analysis.pdf).
## Repository Structure

```
├── data
├── images
├── README.md
├── Aviation Company Risk Analysis.pdf
└── aviation_company_risk_analysis.ipynb
```
