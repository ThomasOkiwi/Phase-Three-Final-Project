# SyriaTel Company Customers

## Overview
SyraTel Project focuses on analyzing the SyraTel dataset to derive useful insights that may help  telecommunucation operations team, marketing team and customer service team to make data driven decissions; thus minimising risk of revenue loss throught customers' churn.
## Business and Data Understanding
### Stakeholder Audience
The primary stakeholders for this project are individuals and teams within SyraTel, including executives, marketing teams, and customer service representatives. The analysis aims to provide actionable insights for improving business strategies, customer experience, and overall operational efficiency.

### Data Source and Choice
The SyraTel dataset was chosen due to its relevance to the telecommunications industry. It includes information about customer interactions, service usage, and other key metrics. This dataset is crucial for understanding customer behavior, predicting trends, and optimizing business processes.

### Modeling
The modeling phase involves various analytical techniques applied to the dataset. The Jupyter Notebook in this repository contains the detailed code and implementation. Logistic Regression was used as the firsrt model. Accuracy of this model was 85% which was satifactory but not the best. We then introduced other model to get better performace.

![image](https://github.com/ThomasOkiwi/Phase-Three-Final-Project/assets/133016687/3a317cc2-c274-416f-80e4-ad059827c246)


### Model Evaluation
The evaluation section provides a comprehensive review of the model performance and the effectiveness of the analysis. Data was testes againd serveral models including : 
Logist Regressin, Random Forest, Decision Tree, K-Nearest Neighbour and Ensembel Method. Random Forest emerged as the best Model for the detaset with: accuracy- 97%, precision=97% and  recall =97%. Additianally, we used ynthetic Minority Oversampling Technique (SNOTE) to Oversample the  minority data "True", the customers who churned.

![image](https://github.com/ThomasOkiwi/Phase-Three-Final-Project/assets/133016687/70544c54-14f9-497a-a1f6-78e700680442)


## Conclusion
* customer service calls :The frquency of a customer calling customer service ether to raise a concern over the service or requesting for assistance.

* international plan : This is binary value that indicates that a customer has interbatianal call plans or not

* Total Cost: This is the sum of day_charge , evening_charge, and night_charge to get a 24 hours cost of calls
* Total Day minutes : amount of time in minutes spent by costomers on call
* Total day charge: this is the amount of money spent by the users while on call during the day. Probaly the price rate per minute during day is expensive thus leading to churn 
## Recommendations
Review Call Charges:

* Evaluate the pricing structure for calls, especially during the day, and consider revising it to make it more competitive and customer-friendly.
* Introduce promotions or packages that offer cost-effective calling plans, potentially reducing the incentive for customers to churn.

Enhance Customer Service Experience:

* Invest in customer service training to ensure representatives are well-equipped to address and resolve customer issues efficiently.
* Implement measures to reduce customer service wait times, such as increasing staff during peak hours or optimizing the customer care queue system.

Improve Communication with Customers:

* Enhance communication channels to keep customers informed about the status of their service requests, reducing frustration and the need for frequent customer service calls.
* Consider implementing automated systems to provide updates on common issues, allowing customers to get information without having to contact customer service.
