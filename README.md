# Customer Lifetime Value analysis and prediction

## Background of Problem

IBM is a leading high-tech company specialized in providing cognitive solutions and insurance claim processes to B2B customers. The company introduced **IBM Watson**, an advanced AI assistant catering to car insurance claimants.

Facing a decline in overall market performance, including revenue and net income, IBM identified the customer lifetime value (CLV) as a pivotal metric for strategic enhancement. CLV measures the total expected income from a typical customer throughout their relationship with the business. Besides, we identified two major problems of IBM's operational status. 

1. Firstly, the CLV concentrates on a low level, with very few of them scatter in high-CLV intervals. 

2. Secondly, the compensation ratio shows an ascending trend, imposing damages to profits.
IBM's current customer management strategy involves analyzing target customers, allocating resources accordingly, and nurturing selected customers to boost future profitability.

![](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/11e666e38f58595fb64b898b1c61615ea992ab8a/figures/Screenshot%202024-02-04%20205323.png)

## Analytical Process

We built statistical models in response to the two problems. 
1. For the first problem, we built up a K-Means model for differentiated precise marketing. The model divides the consumers into three clusters based on their profile and transaction history. Based on the result, we discussed corresponding strategies of product promotion and customer maintenance with response to each segments. Our promotion strategy is further enhanced by a response-prediction model based on random forest classifier. Data processing and modeling process can be found [here](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/main/kmeans%20copy_all.ipynb)
![]
2. For the second problem, we performed a risk prediction model and identified the significant factors to the risk, which could assist in the adjustment of premium policy and risk assessment schemes.
