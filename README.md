# Churn Analysis of Telco Customers in Power BI

## Overview

Customer churn analysis has become a top priority for companies, as it helps them understand why customers stop using their products or services. By identifying the key factors driving customer churn, businesses can develop targeted strategies to address these issues and improve retention rates.

For this analysis, I created 3 dashboards in Microsoft Power BI to visualize insights from a "Telco customer churn" dataset provided by IBM. Dashboards highlights the customer distribution and the primary reasons customers leave, enabling companies to pinpoint areas for improvement and make data-driven decisions to reduce churn. By leveraging such insights, businesses can strategically invest in solutions to enhance customer satisfaction and loyalty.

## Data Information

The data is from [IBM Telco Customer Churn Dataset](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113_). The Telco customer churn dataset comprises five tables: Demographics, Location, Population, Services, and Status.
These tables are separated into multiple files:

Telco_customer_churn_demographics.xlsx
Telco_customer_churn_location.xlsx
Telco_customer_churn_population.xlsx
Telco_customer_churn_services.xlsx
Telco_customer_churn_status.xlsx

## Data Modeling
In the "Model View" of Power BI, we verify that all tables are properly related before beginning data analysis and visualization.

## Dashbords
### Dashborad Overview

* The total number of customers is 7,043;
* The churn rate is 26.5%;
* Customers have an average satisfaction score of 3.24 on a scale from 0 to 5, suggesting moderate satisfaction;
* The churn rate for male customers is 26.9%, slightly higher than the 26.2% for female customers, showing no significant gender difference in churn behavior;
* Customers without dependents have a high churn rate of 36.6%, compared to just 6.5% for those with dependents, indicating that dependents might contribute to customer loyalty;
* Married customers have a churn rate of 19.7%, much lower than the 33% for non-married customers, suggesting that marital status could be a factor in customer stability;
* Most customers are aged between 35 and 44 years;
* The highest churn rate by age group is among customers aged 75 to 80 years, with a rate of 42.1%;
* The city with the largest number of customers is Los Angeles;
* The city with the highest churn rate is San Diego, at 64.9%, indicating a need for targeted interventions in this area.

## Dashboard Churn Reason
  
* The top 5 churn reasons reveal that lack of competitiveness in service is the primary cause for customer departures;
* Customers who selected Offer E have the highest churn rate at 52.9%, while Offer A has the lowest churn rate at 6.7%, indicating that Offer E may not be meeting customer expectations;
* The majority of customers use Fiber Optic, which also has the highest churn rate at 40.7%. In contrast, customers who don’t have any service have a much lower churn rate of 7.4%;
* The churn rate for Phone Service is 31.8% for customers who have it, compared to 7.4% for those without, highlighting a significant difference in retention;
* Among customers with Phone Service, those who have it show a churn rate of 26.7%, while those who don’t have it have a slightly lower churn rate of 24.9%;
* Customers with Device Protection have a churn rate of 28.7%, compared to 24.9% for those without, suggesting that device protection may not significantly influence churn;
* Customers with Unlimited Data have a churn rate of 31.7%, whereas those without it have a much lower churn rate of 16.0%, indicating that Unlimited Data might be a factor in higher churn.

## Dashborad Contract and Tenure

* Most customers opt for a month-to-month contract, but it has the highest churn rate at 45.8%, whereas the two-year contract has the lowest churn rate at 2.5%;
* Long-term customers prefer the two-year contract, as shown in the "Tenure Year by Number of Customers" graph. On the other hand, those with less than a year of tenure tend to choose the month-to-month contract;
* Customers with a half-year tenure have a notably high churn rate of 53.3%, indicating a critical period for retention efforts;
* Customers with a half-year tenure tend to prefer Offer E, while long-term customers show a preference for Offer A.

## Strategies

I elaborate 6 stratagies from the analysis:

* Improve service offerings by analyzing competitors and providing better value through pricing, quality, or exclusive features;
* Offer incentives for two-year contracts to attract more long-term customers, as they have the lowest churn rate (2.5%);
* Focus on half-year tenure customers with personalized offers or discounts to prevent early churn (53.3% churn rate);
* Investigate why Offer E has high churn (52.9%) and enhance it. Promote Offer A, which has the lowest churn (6.7%);
* Improve service and support for Fiber Optic users, who have the highest churn rate (40.7%), by ensuring quality and reliability;
* Offer family-oriented plans for customers without dependents and create flexible options for non-married customers to reduce churn in these groups.








