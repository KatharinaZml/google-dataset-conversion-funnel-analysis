Conversion funnel & user behaviour analysis using BigQuery
==========================================================
1. Dataset source

This project uses the Google Analytics Sample dataset in BigQuery public datasets:

https://console.cloud.google.com/marketplace/product/obfuscated-ga360-data/obfuscated-ga360-data

2. About the dataset

2.1. Data period & scope

This analysis is based on the Google Analytics sample dataset in BigQuery, which contains a fixed historical snapshot of session-level web analytics data.

The dataset covers the period: 2016-08-01 to 2017-08-01

2.2. Dataset Characteristics
- This is not live or streaming data
- There are no recent or real-time users
- There are no ongoing updates to the dataset
- It represents a static 1-year window of user sessions

2.3. Project implication

All insights — including:

- user behaviour,
- revenue distribution,
- retention,
- and conversion patterns
are derived exclusively from sessions that occurred within this historical 1-year timeframe. This means the analysis reflects historical user behaviour patterns only, not current platform activity.

Consequently, the dataset should therefore be interpreted as: a static, time-bound snapshot of ecommerce user interactions (Aug 2016 - Aug 2017), used for analytical and learning purposes rather than real-time business decision-making.

3. Tables used:

bigquery-public-data.google_analytics_sample.ga_sessions_*

There is no setup required. It is publicly available inside BigQuery.

The objective of this project was to identify:

3.1. Where users drop off in the funnel
Session → product interaction
Product → cart
Cart → purchase

3.2. How converters differ from non-converters

Using:
- behavioral engagement,
- session depth,
- pageviews,
- hits,
- and purchase behavior.

3.3. Which behaviours drive conversion

Including:
- add-to-cart activity,
- funnel progression,
- engagement intensity,
- and repeat interaction patterns.

4. Project Overview

This project analyses user behaviour, retention, conversion dynamics and revenue concentration using the Google Analytics sample e-commerce dataset in BigQuery.

The objective was not only to describe user activity, but to understand:
- where users drop in the funnel,
- which users generate business value,
- how revenue is structurally distributed,
- and which funnel stages represent the highest business impact.

The analysis progresses from descriptive analytics toward business prioritisation and strategic decision-making.
