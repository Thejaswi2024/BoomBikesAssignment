# Project Name : Bike sharing
This project focuses on predicting the demand for shared bikes for BoomBikes, a US-based bike-sharing service, which has faced revenue losses due to the COVID-19 pandemic. The goal is to build a multiple linear regression model to understand the factors influencing bike demand and predict future demand trends.

Using a dataset containing daily bike demand and related factors (such as weather and seasonality), the project aims to:

1.Identify key variables that significantly affect bike demand.
2.Understand how these variables influence demand trends.
3.Help BoomBikes plan effective strategies to meet customer needs, optimize operations, and recover revenue post-lockdown.


## Table of Contents
* General Information
* Technologies Used
* Conclusions
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
The primary goal of this project is to build a multiple linear regression model to predict the demand for shared bikes, using various factors such as weather, seasonality, and time of day. The project aims to understand the factors affecting bike demand and provide actionable insights to improve service delivery for BoomBikes, a US-based bike-sharing company, which has been affected by the COVID-19 pandemic.

- What is the background of your project?
BoomBikes, a leading bike-sharing provider in the US, has faced significant revenue losses due to the COVID-19 pandemic. With social distancing measures and lockdowns in place, bike rentals dropped sharply, affecting the company’s ability to sustain itself.
The company wants to develop a data-driven business plan that will help them better predict bike demand and adjust their operations to meet customer expectations. By understanding demand patterns, BoomBikes can ensure optimal bike availability, reduce operational costs, and make better strategic decisions as they look to bounce back in a competitive market.

- What is the business probem that your project is trying to solve?
*Uncertainty in Demand
*Post-Pandemic Recovery:
*Operational Efficiency:
*Revenue Maximization

- What is the dataset that is being used?
The dataset contains daily data on bike rentals, with independent variables (features) that are believed to influence the demand for bikes. These variables include weather conditions, seasonal factors, and other external factors like holidays. The target variable is the number of bike demand for a given day.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

 1.Intercept (β0 =0.283196) The predicted bike demand when all variables are zero (baseline value).

 2.Positive coefficients (e.g., temp, yr): These indicate a positive relationship with bike demand. For example, for every 1-unit increase in temperature, bike demand increases by 0.527708

 3.Negative coefficients (e.g.weathersit_Light Snow): These indicate a negative relationship with bike demand by -0.245009
 4.Increase bike availability and marketing efforts during summer and September, as these months show a strong positive impact on demand. Optimize operations in winter, where there is a moderate positive effect, by ensuring bikes are well-maintained and available in areas where demand remains steady.

 5.Address Weather Challenges: Since high humidity, windspeed, and light snow reduce demand, provide weather-appropriate bikes (e.g., electric bikes for wind resistance) and shelters at bike stations.

 6.Increase availability and promotions on Saturdays, as demand slightly rises on weekends. Consider offering weekend discounts to boost demand on Sundays, where usage is lower.

 7.Maximize Demand During the Year: Capitalize on the positive growth trend by expanding services during the year to accommodate rising customer numbers.

 8.Optimize for Holidays: Create special offers or incentives during holidays to counteract the drop in demand. Partnerships with events or tourist attractions could encourage bike rentals during these times.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

numpy 1.26.4
pandas 2.2.2
seaborn 0.13.2
matplotlib 0.13.2
statsmodels 0.14.2
sci-kit learn 1.4.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by the need for data-driven decision-making in the bike-sharing industry, particularly as it relates to predicting demand patterns and optimizing operations.



## Contact
Created by @Thejaswi2024 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->