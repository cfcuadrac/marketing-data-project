# marketing-data-project

This project is based on a real world dataset from Olist, a large online marketplace in Brazil that helps small and medium sized businesses sell to customers all over the country.

The dataset covers the full sales funnel, from the moment a lead first interacts with Olist’s marketing (top of the funnel) to the moment that lead becomes a closed deal (bottom of the funnel). This gives a full view of the customer journey from first contact to deal won, making it possible to see how leads move through the process and where they drop off.

Because the data includes both marketing and sales information, it can be used to study conversion rates, sales representative performance, and the traits of different leads. This helps answer questions like which marketing sources bring the best leads, which behavior profiles close faster or for higher amounts, and how sales results change across business segments.

In this project, I will use Python to clean and explore the data, and Tableau to create an interactive dashboard that shows the main findings in a clear and visual way. The goal is to find patterns, spot issues, and suggest improvements that could help Olist’s marketing and sales teams work more effectively.

The 4 business questions:
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

Link for the dataset:
- https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist?utm_source=chatgpt.com&select=olist_closed_deals_dataset.csv
