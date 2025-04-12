# Mobile-Device-Usage-Analysis

##  Overview
This project aims to analyze mobile device usage patterns and user behavior using a dataset comprising various features, including app usage time, screen-on time, battery consumption, and data usage. The primary objective is to predict user behavior classes and derive meaningful insights into mobile usage trends.

By examining these attributes, the study seeks to uncover valuable insights that can inform app development strategies, optimize device performance, and enhance user engagement models. A key focus of the analysis is the segmentation of data based on age and gender to identify patterns and trends across different demographic groups. This includes assessing variations in data consumption, screen-on time, and app usage, as well as analyzing the distribution of user behavior classes across diverse user categories.

 ## Business Problem
 People use their mobile phones in different ways—some use them minimally, while others are heavy users. Businesses, such as app developers and mobile service providers, need to understand user behavior to optimize services, recommend relevant apps, and improve battery management.By predicting user behavior class, companies can:
* Provide personalized app recommendations.
* Optimize mobile network data plans.
* Improve battery performance and user experience.

## Business Objectives
* Understand User Behavior & Mobile Usage Trends: Conduct a comprehensive exploratory data analysis (EDA) to identify user behavior patterns, app usage trends, and battery consumption insights, enabling data-driven strategies for user engagement and product optimization.

* Enhance Decision-Making with Visual Analytics: Develop an interactive Power BI dashboard to track key metrics such as app usage time, screen time, battery drain, and user segmentation, providing actionable insights for business growth.
## Dataset 
This dataset provides a comprehensive analysis of mobile device usage patterns and user behavior classification. It contains 700 samples of user data, including metrics such as app usage time, screen-on time, battery drain, and data consumption. Each entry is categorized into one of five user behavior classes, ranging from light to extreme usage, allowing for insightful analysis and modeling.

Key Features:
* User ID: Unique identifier for each user.
* Device Model: Model of the user's smartphone.
* Operating System: The OS of the device (iOS or Android).
* App Usage Time: Daily time spent on mobile applications, measured in minutes.
* Screen On Time: Average hours per day the screen is active.
* Battery Drain: Daily battery consumption in mAh.
* Number of Apps Installed: Total apps available on the device.
* Data Usage: Daily mobile data consumption in megabytes.
* Age: Age of the user.
* Gender: Gender of the user (Male or Female).
* User Behavior Class: Classification of user behavior based on usage patterns (1 to 5).

## Key Findings and Insights

## User Behavior Summary Table

| Feature              | Average         | Median          | Minimum | Maximum       | Key Insight                                      |
|----------------------|----------------|------------------|---------|---------------|--------------------------------------------------|
| **Apps Installed**    | 50 apps        | 49 apps         | 10      | 99            | Fairly normal distribution of app count.         |
| **App Usage Time**        | 271 min/day    | 227.5 min/day   | 30      | 598           | Skewed by heavy users, avg ≈ 4.5 hours.          |
| **Screen On Time**        | 5.27 hrs/day   | 4.9 hrs/day     | 1       | 12            | Most users spend 5+ hours/day on screen.         |
| **Battery Drain**         | 1525 mAh/day   | 1502.5 mAh/day  | 302     | 2993          | Consistent usage with some power users.          |
| **Data Usage**            | 929.74 MB/day  | 823.5 MB/day    | 102     | 2560 (2.5 GB) | High variance in data consumption.               |
| **User Age**              | 38.48 years    | 38 years        | 18      | 59            | Adult-dominant user base, evenly distributed.    |


##  Mobile Usage Patterns by Device Model
iOS users consistently show higher values in Screen On Time, Battery Drain and App Usage Time. This suggests iOS users tend to use their devices more intensively than Android users.

## Correlation Analysis: App Usage, Screen Time & Battery Drain
-  App Usage Time ↔ Battery Drain: Correlation of 0.96
-  Screen-On Time ↔ Battery Drain: Correlation of 0.95
-  These strong correlations imply that users who spend more time on apps and screens tend to drain battery faster.
- These metrics are useful predictors for battery optimization and usage behavior.

## Demographic Analysis
- Gender-based insights: App Usage Time and Screen-On Time are similar across genders.
- Age-based usage patterns: Males below 20 years show the highest app and screen usage.Females aged 30–39 exhibit the most intensive usage in their category.

## Data Consumption Analysis

- Average Daily Data Usage by User Behavior Class: Users in Class 5 (extreme usage) consume the most data, while Class 1 (light usage) consumes the least. The data usage trend follows this pattern: 1 < 2 < 3 < 4 < 5.
- Device-Specific Usage Patterns: Samsung Galaxy S21 and Xiaomi Mi 11 users, particularly in Class 5, have the highest daily data usage.


- These insights are critical for app developers and mobile service providers to tailor services, data plans, and optimize user experiences across demographics and platforms.












