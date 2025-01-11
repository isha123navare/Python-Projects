# PROJECT 1: MAXIMIZING REVENUE FOR DRIVERS
## Dataset Link: 
https://drive.google.com/file/d/1SRGTB3-LJVDsVQfMtR322Ihtv1uoLswi/view?usp=sharing

## Dataset Contains:
VendorID, tpep_pickup_datetime, tpep_dropoff_datetime, passenger_count, trip_distance, RatecodeID, store_and_fwd_flag, PULocationID, DOLocationID, payment_type, fare_amount, extra, mta_tax, tip_amount, tolls_amount, improvement_surcharge, total_amount, congestion_surcharge

## Link to Google Colab: 
https://colab.research.google.com/drive/13A0cMHlxFjwadDT914KdphhIkUUcp2Iy?usp=sharing

## Problem Statement
In the fast-paced taxi booking sector, making most of revenue is essential for long-term success and driver happiness. In the fast-paced taxi booking sector, making most of revenue is essential for long-term success and driver happiness. In the fast-paced taxi booking sector, making most of revenue is essential for long-term success and driver happiness. Our goal is to use data-driven insights maximise revenue streams for taxi drivers in order meet this need. This project aims to determine whether payment methods have an impact on fare pricing by focusing the relationship between type and amount.

## Research Question
Is there a relationship between fare amount and payment type? Can we nudge customers towards payment methods that generate higher revenue for drivers without negatively impacting customer experience?

## Data Overview
For this analysis, we utilized the comprehensive dataset of NYC Taxi Trip records, used data cleaning and feature engineering procedures to concentrate solely on the relevant columns essential for our investigation.

## Methodology
1. Descritpive Analysis: Performed statistical analysis to summarize key aspects of the data, focusing on fare amounts and payment types.
2. Hypothesis Testing: Conducted a T-test to evaluate the relationship between payment type and fare amount, testing the hypothesis that different payment methods influence fare amounts.
3. Regression Analysis: Implemented linear regression to explore the relationship between trip duration (calculated from pickup and dropoff times) and fare amount.

## Relevant columns used for this reseach
1. passenger_count (1 to 5)
2. payment_type (card or cash)
3. fare_amount
4. trip_distance (miles)
5. duration (minutes)

## Insights, Observations, & Key Takeaways

1. Journey Insights:
   
a. Customers paying with cards tend to have a slightly higher average trip distance and fare amount compared to those paying with cash.

b. Indicates that customers prefers to pay more with cards when they have high fare amount and long trip distance.

2. Preference of Payment Types:

a. The proportion of customers paying with cards is significantly higher than those paying with cash, with card payments accounting for 65% of all transactions compared to cash payments at 35%.

b. This indicates a strong preference among customers for using card payments over cash, potentially due to convenience, security, or incentives offered for card transactions.

3. Passenger Count Analysis:

a. Among card payments, rides with a single passenger (passenger_count = 1) comprise the largest proportion, constituting 41% of all card transactions.

b. Similarly, cash payments are predominantly associated with single-passenger rides, making up 22% of all cash transactions.

c. There is a noticeable decrease in the percentage of transactions as the passenger count increases, suggesting that larger groups are less likely to use taxis or may opt for alternative payment methods.

4. Hypothesis Testing:

Null hypothesis: There is no difference in average fare between customers who use credit cards and customers who use cash.

Alternative hypothesis: There is a difference in average fare between customers who use credit cards and customers who use cash.

With a T-statistic of 93.454 and a P-value of less than 0.05, we reject the null hypothesis, suggesting that there is indeed a significant difference in average fare between the two payment methods.

## Recommendations:

1. Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue for taxi cab drivers.
   
2. Implement strategies such as offering incentives or discounts for credit card transactions to incentivize customers to choose this payment method.

3. Provide seamless and secure credit card payment options to enhance customer convenience and encourage adoption of this preferred payment method.













