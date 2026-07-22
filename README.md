# Will a Customer Accept the Coupon?

## Context
When a coupon is delivered to a driver's cell phone while they are driving, there are various factors that may influence whether they accept it, including the type of business (restaurant, bar, coffee house), presence of passengers, weather conditions, time of day, and proximity to the business. Understanding these factors can help predict whether a driver is likely to accept a coupon and take a detour to the business.

## Overview
The goal of this project is to analyze survey data collected via Amazon Mechanical Turk to determine the factors that influence whether a driver accepts a coupon. By leveraging visualizations and probability distributions, we aim to distinguish between customers who accepted a driving coupon versus those who did not.

This project aims to analyze the acceptance rates of Bar coupons and Coffee House coupons among drivers and passengers based on various demographic factors such as marital status, income, occupation, education level, gender, age, number of children, and environmental factors such as weather, temperature, and time etc. By exploring how these factors influence coupon acceptance, businesses can better understand their target audience and optimize their marketing strategies accordingly.

## Data
- **Source**: UCI Machine Learning Repository
- **Collection Method**: Survey on Amazon Mechanical Turk
- **Format**: Survey responses
- **Labels**: 'Y = 1' for accepting the coupon ('right away' or 'later before the coupon expires'), 'Y = 0' for not accepting the coupon
- **Types of Coupons**:
  - Less expensive restaurants (under $20)
  - Coffee houses
  - Carry out & take away
  - Bars
  - More expensive restaurants ($20 - $50)

## Deliverables
- Identification of key differences between customers who accepted and those who did not accept the coupons.
- Utilization of Python for plotting, statistical summaries, and visualization.
- Findings published in a public-facing GitHub repository as the first portfolio piece.

---

## Findings

### Use Case#1: Bar Coupon Acceptance Analysis

1. **Proportion of Total Observations Accepted the Coupon**:
   - Proportion: 56.93%
   - The overall proportion of coupon acceptance is higher than the proportion of rejections, suggesting the effectiveness of the coupon distribution strategy or the attractiveness of the offers themselves.

2. **Proportion of Bar Coupons Accepted**:
   - Proportion: 41.19%
   - To improve the acceptance rate of bar coupons, further analysis might be needed to understand the drivers' preferences and adjust the marketing strategy.

3. **Acceptance Rate Based on Frequency of Bar Visits**:
   - For individuals who visit bars 3 or fewer times a month: 64.64%
   - For those who visit bars more than 3 times a month: 76.16%
   - Targeting individuals who visit bars more frequently with bar coupons might be a more effective strategy.

4. **Age and Acceptance Rates**:
   - Acceptance rate for drivers over the age of 25: 68.98%
   - Acceptance rate for drivers under the age of 25: 67.45%
   - Older drivers are marginally more likely to accept bar coupons.

5. **Passenger Type and Occupation**:
   - Acceptance rate for drivers with adult passengers and occupations other than farming, fishing, or forestry: 70.94%
   - Drivers with higher-paying occupations and frequent bar visits are more receptive to bar coupons.

6. **Demographic Patterns**:
   - Drivers who go to bars more than once a month and have lower incomes show relatively high acceptance rates.

### Use Case#2: Coffee House Coupon Acceptance Analysis

1. **Marital Status and Acceptance Rates**:
   - Divorced: 51.75%
   - Married partner: 49.11%
   - Single: 51.44%
   - Unmarried partner: 47.04%
   - Widowed: 35.29%
   - Divorced and single individuals show relatively higher acceptance rates for coffee house coupons.

2. **Income and Acceptance Rates**:
   - Acceptance rates vary across income categories, with notable fluctuations.
   - Middle-income passengers demonstrate moderate to high acceptance rates.

3. **Education Level and Acceptance Rates**:
   - Passengers with higher levels of education tend to have higher acceptance rates for coffee house coupons.
   - Higher education attainment may be associated with a greater propensity to accept coffee house coupons.

## Conclusion

The analysis reveals that acceptance rates for bar and coffee house coupons vary significantly based on demographic factors such as marital status, income, and education level. These findings provide valuable insights for businesses seeking to target specific customer segments with promotions.
