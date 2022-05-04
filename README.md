# EDA and RFM Analysis on Brazilian E-Commerce Public Dataset by Olist

![image](https://user-images.githubusercontent.com/85127229/166829582-bf6b01f8-0d72-479f-be2a-1aa4436726cb.png)

## About the dataset:

Mostly quoted from the data description in Kaggle

This is a Brazilian ecommerce public dataset of orders made at Olist Store (https://olist.com/pt-br/). The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.

This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.

Olist has also released a Marketing Funnel Dataset (https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist). You may join both datasets and see an order from Marketing perspective. The dataset has information of 8k Marketing Qualified Leads (MQLs) that requested contact between Jun. 1st 2017 and Jun 1st 2018. They were randomly sampled from the total of MQLs.

The term MQL means a potential reseller/manufacturer who has an interest in selling its products on Olist.

The values of feature lead_behavior_profile is related to DISC personality test. But when translating to portuguese they related the behaviour profiles to animals.

    Shark - Dominance

    Eagle - Influence

    Cat - Steadiness

    Wolf - Conscientiousness

Moreover, Deal close means that the lead paid the subscription and joined the platform.

Regarding the conversion rate, you can also check the discussion board of the dataset (https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist/discussion/72388)

Features of dataset allows viewing a sales process from multiple dimensions: lead category, catalog size, behaviour profile, etc.

Every data is also real data, it has been anonymized and sampled from the original dataset.


## Data Schema:

The data is divided in multiple datasets for better understanding and organization. We can refer to the following data schema when working with it:

![image](https://user-images.githubusercontent.com/85127229/166829921-91c4c200-d66d-4f30-ba6b-da97d6a09b97.png)

From the commercial data schema above, we can analyze the sales and delivery performance of Olist.

![image](https://user-images.githubusercontent.com/85127229/166830023-91aa71c9-aa2a-4184-934d-51e61ec5bd17.png)

From the marketing funnel data, we can analyze the marketing performance. This analysis is not included in this repository.


