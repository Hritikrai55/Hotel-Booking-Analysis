# Hotel Booking Analysis

## Project Overview

This project aims to analyze booking data for two types of hotels: City Hotel and Resort Hotel. The dataset comprises 119,390 records and 32 columns. The analysis is conducted using a structured workflow that includes the following phases:

1. **Data Collection and Understanding**
2. **Data Cleaning and Manipulation**
3. **Exploratory Data Analysis (EDA)**

## Summary

The project begins with Data Collection and Understanding, where key columns such as `hotel`, `is_canceled`, `lead_time`, and others are identified. The dataset’s structure is examined, and essential columns are updated for clarity. In the Data Cleaning phase, duplicate records are addressed, resulting in the removal of 87,396 duplicate entries. Missing values are handled using data wrangling techniques, including the `drop()` method for columns with significant missing data and the `fillna()` method for minimal null values.

During the EDA phase, various charts and graphs are used to uncover patterns and trends within the dataset. Insights derived include identifying peak booking seasons, analyzing average lead times, and evaluating cancellation rates across different hotel types. These insights are crucial for hotel management to make data-driven decisions regarding pricing, marketing, and staffing.

## Business Objective

The primary goal is to analyze booking data for both City and Resort Hotels to gain insights into factors that influence the booking process. This analysis can help hoteliers optimize operations, improve customer satisfaction, and increase revenue.

## Key Insights and Recommendations

- **Popularity and Revenue**: City Hotels are more popular and generate higher revenue compared to Resort Hotels. Peak booking months are July and August, with the majority of bookings originating from Portugal and Great Britain.
  
- **Booking Duration and Retention**: Guests typically stay for 1-4 days. City Hotels have a higher retention rate, suggesting a focus on expanding offerings at these locations.
  
- **Cancellation Rate**: With a 27% cancellation rate, implementing a robust cancellation policy is crucial. Analyzing cancellation reasons and improving booking experiences can help reduce this rate.
  
- **Booking Channels**: Direct and TA/TO (Tour Operators/Travel Agents) channels contribute equally to the Average Daily Rate (ADR). Continuing partnerships with tour agents and operators is recommended.

- **Yearly Trends**: The year 2016 saw the highest number of bookings, whereas 2015 had fewer than 7,500 bookings. Special promotions and incentives could boost bookings during slower years.

- **Seasonal Promotions**: Summer months show a higher ADR for Resort Hotels. Promoting vacation packages during this period could attract more guests.

## Conclusion

This project underscores the value of data science techniques in extracting actionable insights from hotel booking data. By following a structured workflow, the analysis provides valuable information that can help hotel management optimize pricing strategies, enhance marketing efforts, and improve overall operations.
