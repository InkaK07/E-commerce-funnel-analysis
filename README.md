# E-commerce-funnel-analysis

Below are selected screenshots from the Power BI dashboard created for this analysis.

![Funnel Overview]([funnel_overview_with_anomaly.png](https://github.com/InkaK07/E-commerce-funnel-analysis/blob/main/funnel_overview_with_anomaly.png)) 

![Funnel Overview-without anomaly]([funnel_overview_without_anomaly.png](https://github.com/InkaK07/E-commerce-funnel-analysis/blob/main/funnel_overview_without_anomaly.png)) 

![Median Conversions]([median_conversions_time_price.png](https://github.com/InkaK07/E-commerce-funnel-analysis/blob/main/median_conversions_time_price.png))


## Project Overview
This project explores and analyses user behaviour in an e-commerce setting using event-level data.  
The goal is to clean the dataset, explore customer interactions, and derive insights related to conversion behavior, timing, and purchasing patterns.

The analysis focuses on understanding how users move through the e-commerce funnel and where drop-offs occur.

---

## Dataset
The dataset contains anonymised e-commerce events with the following key columns:

- `event_time` — Timestamp of the event
- `event_type` — Type of event (`view`, `cart`, `purchase`)
- `price` — Product price at time of purchase
- `user_id` — Unique user identifier
- `user_session` — Session identifier

Events represent typical stages in an e-commerce funnel:
- **View → Cart**
- **View → Purchase**
- **Cart → Purchase**

A conversion is defined as a **purchase event**.

---

## Funnel Definition
The e-commerce funnel analysed in this project consists of:

1. View
2. Cart
3. Purchase

Users may skip steps (e.g., View → Purchase).

---

## Key Questions Addressed
This analysis answers the following questions over 6 months:

1. What is the distribution of events over time?
2. Where is the biggest drop-off in the funnel, and at which stage?
3. What is the overall conversion rate?
4. What is the median time to purchase?
5. What is the median purchase price?
6. How are purchases distributed by hour of day?
7. Which product categories generate the highest sales?

---

## Analysis Structure
The project follows these steps:

1. Data cleaning and preprocessing
2. Exploratory data analysis (EDA)
3. Funnel analysis
4. Time-to-purchase analysis
5. Pricing and category insights
6. Visualisation of key metrics

---

## Data Source & Acknowledgements
The dataset used in this project was sourced from publicly available e-commerce event data provided by **REES46**.

REES46 is a marketing automation platform specialising in personalisation and recommendation systems for e-commerce.

🔗 REES46 Marketing Platform: https://rees46.com/

This project is for educational and analytical purposes only.
