# Customer Personality Analysis via PCA and Clustering

## Results
I was able to identify 5 rather small clusters by using OPTICS clustering after applying data cleaning, feature engineering and PCA on the data. Only 40% of the customers got assigned to a cluster.

| Cluster | Income (Category) | Children | Spending | Marketing Response | Partner | Age in Years |
|---------|-------------------|----------|----------|--------------------|---------|-----|
| 0       | High              | None     | High     | High               | Yes     | Around 50 |
| 1       | Low               | 1 Kid    | Low      | No                 | No      | Around 34 |
| 2       | Low               | 1 Kid    | Low      | No                 | Yes     | Around 34 |
| 3       | Moderate          | 1 Teen, 1 Kid | Low | No              | No      | Around 50 |
| 4       | Moderate          | 1 Teen, 1 Kid | Low | No              | Yes     | Around 50 |

- Cluster 0: Wealthy, childless individuals around 50 years old, mostly with a partner, who spend significantly and respond well to marketing campaigns.
- Cluster 1: Lower-income, young single parents in their mid-thirties with one child, who spend minimally and are unresponsive to marketing.
- Cluster 2: Lower-income young families, also in their mid-thirties, with a partner and one child, displaying similar low spending and marketing non-responsiveness as Cluster 1.
- Cluster 3: Moderate-income, single parents around 50 years old, with one teen and one child, who spend little and do not respond to marketing efforts.
- Cluster 4: Moderate-income families around 50 years old, with a partner, one teen, and one child, exhibiting low spending and no marketing response, similar to Cluster 3 but with a partner.

## Context

Understanding and analyzing customer behavior is crucial for businesses to thrive in today's competitive market. Customer Personality Analysis offers a detailed examination of a company’s target customer profiles, aiding in product customization and targeted marketing strategies. Clustering enables the company to identify groups of customers to better adress those and maximize the revenue.
## Dataset Attributes

The data originates from [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).
### People

- **ID**: Unique identifier for each customer
- **Year_Birth**: Year of birth of the customer
- **Education**: Level of education attained by the customer
- **Marital_Status**: Marital status of the customer
- **Income**: Yearly household income of the customer
- **Kidhome**: Number of children in the customer's household
- **Teenhome**: Number of teenagers in the customer's household
- **Dt_Customer**: Date of customer's enrollment with the company
- **Recency**: Number of days since the customer's last purchase
- **Complain**: Indicates whether the customer complained in the last 2 years (1 for yes, 0 for no)

### Products

- **MntWines**: Amount spent on wine in the last 2 years
- **MntFruits**: Amount spent on fruits in the last 2 years
- **MntMeatProducts**: Amount spent on meat in the last 2 years
- **MntFishProducts**: Amount spent on fish in the last 2 years
- **MntSweetProducts**: Amount spent on sweets in the last 2 years
- **MntGoldProds**: Amount spent on gold in the last 2 years

### Promotion

- **NumDealsPurchases**: Number of purchases made with a discount
- **AcceptedCmp1-5**: Indicates whether the customer accepted the offer in each of the 5 campaigns (1 for yes, 0 for no)
- **Response**: Indicates whether the customer accepted the offer in the last campaign (1 for yes, 0 for no)

### Place

- **NumWebPurchases**: Number of purchases made through the company’s website
- **NumCatalogPurchases**: Number of purchases made using a catalogue
- **NumStorePurchases**: Number of purchases made directly in stores
- **NumWebVisitsMonth**: Number of visits to company’s website in the last month

 More infromation can be found on the webpage.