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

All insights, including user behaviour, revenue distribution and conversion patterns, are derived exclusively from:
- sessions that occurred within this 1-year historical timeframe

-> This means the analysis reflects historical user behaviour patterns only, not current platform activity.


Specifically, the dataset should be interpreted as a static, time-bound snapshot of user interactions (Aug 2016 to Aug 2017), used for analytical and learning purposes rather than real-time decision-making.

3. Tables used:

bigquery-public-data.google_analytics_sample.ga_sessions_*

There is no setup required. It is publicly available inside BigQuery.

4. Project goal

Identification of:
3.1. Where users drop-off in the funnel
3.2. How converters differ from non-converters
3.3. Which behaviours and product categories drive conversion


