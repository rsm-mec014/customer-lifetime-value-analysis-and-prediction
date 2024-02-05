# Customer Lifetime Value analysis and prediction

## Background of Problem

IBM is a leading high-tech company specialized in providing cognitive solutions and insurance claim processes to B2B customers. The company introduced **IBM Watson**, an advanced AI assistant catering to car insurance claimants.

Facing a decline in overall market performance, including revenue and net income, IBM identified the customer lifetime value (CLV) as a pivotal metric for strategic enhancement. CLV measures the total expected income from a typical customer throughout their relationship with the business. We identified two major problems of IBM's customer value status. 

1. Firstly, the CLV concentrates on a low level, with very few of them scatter in high-CLV intervals. 

2. Secondly, the compensation ratio shows an ascending trend, imposing damages to profits and net CLV.
IBM's current customer management strategy involves analyzing target customers, allocating resources accordingly, and nurturing selected customers to boost future profitability.

![](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/11e666e38f58595fb64b898b1c61615ea992ab8a/figures/Screenshot%202024-02-04%20205323.png)

## Analytical Process

We built several statistical models in response to the two problems. 
1. For the first problem, we built up a **K-Means** model for differentiated precise marketing. Based on the result, we discussed corresponding strategies of product promotion and customer maintenance with response to each segments. Our promotion strategy is further enhanced by a response-prediction model based on **random forest** classifier. Data processing and modeling process can be found [here](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/main/kmeans%20copy_all.ipynb).
![K-Means Model](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/83355b7c49212788b48c9112a6c8ad32e4686883/figures/Screenshot%202024-02-04%20212410.png)
2. For the second problem, we performed a risk prediction model and identified the significant factors to the risk, which could assist in the adjustment of premium policy and risk assessment schemes. Model with a comparison on statistical level can be viewed [here](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/2d5a2b83809cb17a4b2720b99cd32e895620d1ad/response%20pred.ipynb)
![Risk Prediction Model](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/83355b7c49212788b48c9112a6c8ad32e4686883/figures/Screenshot%202024-02-04%20205524.png)

## Result and Analysis
We analyzed features of three customer groups divided by the K-Means model, and pictured their representative profile in the figure below.
![Customer Profile](https://github.com/rsm-mec014/customer-lifetime-value-analysis-and-prediction/blob/83355b7c49212788b48c9112a6c8ad32e4686883/figures/Screenshot%202024-02-04%20205445.png)

- For high-income individuals with luxury cars, IBM can provide tailored insurance solutions that address their specific needs. This includes specialized coverage such as glass breakage and car scratch insurance, which may be essential for luxury vehicles. Enhancing service quality is crucial to elevate customer satisfaction, necessitating investments in personnel training and resource allocation. Personal selling, such as assigning a dedicated receptionist to high-income clients, establishes a direct and personalized connection.

- For corporate employees, partnering with business vehicle dealers, such as 4S car shops, allows direct sale of insurance when companies purchase vehicles. Corporations exhibit greater stability and less elasticity in auto insurance preferences, enabling the establishment of longer contracts and the provision of reliable services, thus extending the corporate consumer lifetime.

- In targeting the mass market, focusing on the size of the consumer base takes precedence over individual CLV. A penetration strategy, incorporating market penetration pricing and digital advertising, can attract a larger consumer base, ultimately increasing the total CLV for this segment.
