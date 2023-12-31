# Statistical Review and A/B Testing for New York City TLC Project

## Overview
The purpose of this project is to predict taxi cab fares before each ride, with a primary focus on finding ways to generate more revenue for New York City taxi cab drivers. Specifically, this part of the project examines the relationship between total fare amount and payment type.

## Problem
Taxi cab drivers receive varying amounts of tips. While investigating the relationship between total fare amount and payment type, this project aims to discover if customers who pay with credit cards tend to pay a larger total fare amount compared to customers who pay with cash.

## Solution
The Automatidata team conducted an A/B test to analyze the relationship between credit card payment and total fare amount. The key business insight from this analysis is that encouraging customers to pay with credit cards is likely to generate more revenue for taxi drivers.

## Project Details
### Steps conducted in the A/B test
1. Collected sample data from an experiment in which customers were randomly selected and divided into two groups:
   - Customers required to pay with a credit card.
   - Customers required to pay with cash. This enables us to draw causal conclusions about how payment method affects fare amount.
2. Computed descriptive statistics to better understand the average total fare amount for each payment method available to the customer.
3. Conducted a two-sample t-test to determine if there is a statistically significant difference in the average total fare between customers who use credit cards and customers who use cash.

### A/B Test Results
There is a statistically significant difference in the average total fare between customers who use credit cards and customers who use cash. Customers who used credit cards showed a higher total amount compared to cash.

## Next Steps
The Automatidata data team recommends that the New York City TLC encourages customers to pay with credit cards and creates strategies to promote credit card payments. For example, the New York City TLC can install signs that read "Credit card payments are preferred" in their cabs and implement a protocol that requires cab drivers to verbally inform customers that credit card payments are preferred.


