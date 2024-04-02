## Dataset Overview: Customer Personality Analysis

### Context

Understanding and analyzing customer behavior is crucial for businesses to thrive in today's competitive market. Customer Personality Analysis offers a detailed examination of a company’s target customer profiles, aiding in product customization and targeted marketing strategies.

### Problem Statement

The dataset serves as a tool for businesses to gain deeper insights into their customers, empowering them to tailor products and services based on specific customer needs, behaviors, and preferences across various segments.

### Dataset Attributes

#### People

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

#### Products

- **MntWines**: Amount spent on wine in the last 2 years
- **MntFruits**: Amount spent on fruits in the last 2 years
- **MntMeatProducts**: Amount spent on meat in the last 2 years
- **MntFishProducts**: Amount spent on fish in the last 2 years
- **MntSweetProducts**: Amount spent on sweets in the last 2 years
- **MntGoldProds**: Amount spent on gold in the last 2 years

#### Promotion

- **NumDealsPurchases**: Number of purchases made with a discount
- **AcceptedCmp1-5**: Indicates whether the customer accepted the offer in each of the 5 campaigns (1 for yes, 0 for no)
- **Response**: Indicates whether the customer accepted the offer in the last campaign (1 for yes, 0 for no)

#### Place

- **NumWebPurchases**: Number of purchases made through the company’s website
- **NumCatalogPurchases**: Number of purchases made using a catalogue
- **NumStorePurchases**: Number of purchases made directly in stores
- **NumWebVisitsMonth**: Number of visits to company’s website in the last month

### Target

Clustering analysis to summarize customer segments.
