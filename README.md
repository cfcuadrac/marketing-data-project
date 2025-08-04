# marketing-data-project

This project is based on a real world dataset from Olist, a leading virtual marketplace in Brazil that connects small and medium sized businesses to customers nationwide.

The dataset captures the entire sales funnel, from the moment a lead first engages with Olist’s marketing efforts (top of the funnel) to the point when that lead becomes a closed deal (bottom of the funnel). This provides a complete view of the customer acquisition journey from first contact to deal won, allowing for in depth analysis of conversion rates, sales performance, and lead characteristics.

In this project, I will analyze the data to uncover patterns, identify bottlenecks, and generate actionable insights that could help optimize both marketing and sales strategies.

The 4 business questions I want to answer with this data set are the following:
  1. Which marketing origins produce the highest conversion rate to closed deals?
  2. How long does it take for a lead to move from first contact to deal won on average (by origin)?
  3. Which SDRs or SRs close the most deals, and do they specialize in certain business segments?
  4. Do certain lead behaviour profiles (cat, wolf, eagle, etc.) lead to higher deal values or quicker closes?

The plan for the week:

Monday - Dataset understanding and questions
  - Select the data, explore it and see what is the key information I need to use for each question.
  - Start cleaning the data and removing all unnecessary information.
  - Merge datasets
  - Create GitHub repo and upload all the csv's, and jupyter notebook with the necessary info.

Tuesday - Data Cleaning & Wrangling
  - Handle missing values:
      - declared_monthly_revenue, average_stock, has_gtin
  - Create new calculated fields such as conversion_rate, days_to_close
  - Change all the formats of the columns to the needed formats
  - Create a new csv with clean data

Wednesday - EDA
  - Calculate:
      - Conversion rates
      - Average days to close by origin
      - Top SDR AND SRs by number of deals and business segment
      - Deal value and time-to-close by lead beahviour profile
  - Creat plots to confirm insights on Python
  - Export cleaned data set to Tableau

Thursday - Tableau Dashboard and Presentation
  - Import cleaned data set
  - Build dashboards:
      - Funnel overview (MQLs → Deals)
      - Conversion rate by marketing origin
      - Time-to-close by origin
      - SDR/SR performance leaderboard
      - Behaviour profile analysis
  - Create canva presentation
