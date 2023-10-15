# CLTV-Prediction-With-BG-NBD-and-Gamma-Gamma


FLO is a large online retail store of Turkey. FLO store, which includes shoes, bags and sports products in Women's, Men's and Children's categories, has a large transaction volume.

FLO, an online shoe store, wants to segment its customers and determine marketing strategies according to these segments. To this end, the behaviors of the customers will be defined and groups will be formed according to the clusters in these behaviors.

![flo-magaza](https://github.com/oktaydoganyildiz/Customer-Segmentation-with-RFM/assets/70387935/63b3f79c-2f88-410e-a132-3a9b3372172c)

# Business Problem 👩‍💻
FLO wants to set a roadmap for sales and marketing activities. In order for the company to make a medium-long-term plan, it is necessary to estimate the potential value that existing customers will provide to the company in the future.


# BG-NBD and Gamma Gamma

BG/NBD Model (Beta Geometric / Negative Binomial Distribution) 

Beta geometric distribution and negative binomial distribution are discrete probability distributions studied in the branches of statistics and probability sciences.In addition, the BG/NBD model is a probabilistic model that is also used as a stand-alone sales forecasting model. BG/NBD probabilistically models two processes for the expected number of transactions: Purchasing process: Transaction rates vary for each customer and are gamma distributed for the entire audience. Dropout process (Churn): Dropout rate varies for each customer and beta is distributed for the entire audience.

![2023-10-15 16_01_41-CLTV-Prediction-With-BG-NBD-ve-Gamma-Gamma_CLTV Prediction With BG-NBD ve Gamma-](https://github.com/oktaydoganyildiz/CLTV-Prediction-With-BG-NBD-ve-Gamma-Gamma/assets/70387935/66d27024-688e-41b0-8003-fcfc2d587b52)

The meanings of the variables used in this formula:

x: Frequency, the number of recurring sales for users who have traded at least twice. t_x: Recency is the time since the customer's first and last purchase. Depending on the approach, it is generally calculated annually, monthly and weekly. T (Tenure): The time between the first time the customer interacts with the company and the time we set the reference. It represents the age of the customer. r, α: Comes from the Gamma distribution. Models the transaction rate. b, a: Models the dropout rate and comes from the beta distribution.

p, q, γ: Transaction values models and come from the gamma distribution, m_x: Monetary refers to the average earnings per purchase, x: Frequency is the number of recurring sales for users who have traded at least twice.

As a result, by multiplying the BG/ NPV and Gamma-Gamma models, creating a time-projected prediction model, CLTV prediction can be achieved across all customers.

Gamma-Gamma Model

It is used to estimate how much profit a customer can bring per transaction on average, and the monetary value of the customer's transactions is randomly distributed around the average of the transaction values. The average transaction value is gamma distributed among all customers.

![image](https://github.com/oktaydoganyildiz/CLTV-Prediction-With-BG-NBD-ve-Gamma-Gamma/assets/70387935/024e136f-3f27-4e65-be27-59da9002cc8f)

p, q, γ: Transaction values models and come from the gamma distribution, m_x: Monetary refers to the average earnings per purchase, x: Frequency is the number of recurring sales for users who have traded at least twice.

![image](https://github.com/oktaydoganyildiz/CLTV-Prediction-With-BG-NBD-ve-Gamma-Gamma/assets/70387935/2bf7d4c7-e59b-4a96-91c8-4e075ccc9b5e)


**As a result, by multiplying the BG/ NPV and Gamma-Gamma models, creating a time-projected prediction model, CLTV prediction can be achieved across all customers.**
