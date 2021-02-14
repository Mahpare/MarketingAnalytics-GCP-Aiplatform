# Marketing-Analytics-GCP-AIplatform
We use a propensity to purchase system to predict customers who are most likely to make a purchase, so that we can personalize communications with them. We can use online predictions to take real-time action based on user behavior on our website, or batch predictions to inform less time-sensitive communications like email.

# Use case:
## Predicting customer propensity to buy in the next 30 days using BigQuery and AI Platform.
The marketeer of the ​Google Merchandise Store​ wants to effectively target visitors of its ecommerce website using paid search. For this reason the marketeer wants to know which visitors, that visited its website on a certain day, are more likely to convert (buy something) in the next 30 days.

The ecommerce store uses Google Analytics to track web visits on its ecommerce website. With the Google Analytics session data it has the availability of historical clickstream data of all its visitors, which includes previous visits, session duration, pageviews, device information, geographical information, transactions, etc.

In this use case, we implement a machine learning workflow:

● Source the data from BigQuery
● Explore and prepare the data
● Code the models
● Train, evaluate and tune the models
● Select the best model
● Deploy the best trained model
● Get predictions from the model


# Source data and data preparation
Google Analytics data of ​Google Merchandise Store​ is available as a public bigquery data set. For this use case we create the input features and the target variable using this data.

Bigquery dataset reference: bigquery-public-data:google_analytics_sample

# Dataset information
The dataset provides 12 months (August 2016 to August 2017) of obfuscated Google Analytics 360 data from the ​Google Merchandise Store​ , a real ecommerce store that sells Google-branded merchandise, in BigQuery. It’s a great way analyze business data

The data is typical of what an ecommerce website would see and includes the following information:

● Traffic source data: information about where website visitors originate, including data about organic traffic, paid search traffic, and display traffic.
● Content data: information about the behavior of users on the site, such as URLs of pages that visitors look at, how they interact with content, etc.
● Transactional data: information about the transactions on the Google Merchandise Store website.


For more information see the ​Google Analytics Sample​ dataset description.
https://console.cloud.google.com/marketplace/product/obfuscated-ga360-data/obfuscated-ga360-data?filter=solution-type:dataset&q=google%20analytics%20sample&id=45f150ac-81d3-4796-9abf-d7a4f98eb4c6
