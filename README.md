# E-commerce-Sales-Behavioral-Analytics-Portfolio-Project
End-to-End E-commerce Analytics: From SQL data extraction (BigQuery) and statistical hypothesis testing in Python to interactive dashboards in Tableau Public
#  E-commerce Sales & Behavioral Analytics Portfolio Project

##  Project Overview
This project is a comprehensive analysis of an online store's performance. It demonstrates a full data workflow: extracting raw data using **SQL**, performing Exploratory Data Analysis (EDA) and **statistical testing in Python**, and building executive **dashboards in Tableau**.

The goal was to identify sales drivers, analyze user behavior (registered vs. guests), and evaluate the effectiveness of marketing channels.

## Tech Stack
- **Data Extraction:** SQL (Google BigQuery)
- **Data Analysis:** Python (Pandas, NumPy)
- **Statistical Analysis:** SciPy, Statsmodels (Correlation, Hypothesis Testing)
- **Visualization:** Matplotlib, Seaborn, Tableau Public

---

## Key Analysis Phases

### 1. SQL Data Engineering
Extracted a custom dataset from BigQuery by joining multiple tables (sessions, orders, products, and users). 
* **Focus:** Ensured all sessions and orders were captured, including guest checkouts.
* **Dimensions:** Geo-data, device details, traffic sources, user subscription status, and product categories.

### 2. Exploratory Data Analysis (Python)
Performed a deep dive into the dataset to answer critical business questions:
* **Geo-Performance:** Identified Top-3 continents and Top-5 countries by revenue and order volume.
* **Product Insights:** Ranked Top-10 categories and compared local vs. global trends.
* **User Engagement:** Analyzed email verification rates and the impact of newsletter unsubscriptions on sales behavior.

### 3. Statistical Analysis & Hypothesis Testing
Moved beyond descriptive statistics to find significant patterns:
* **Correlation Analysis:** Analyzed the relationship between sessions and sales (Pearson/Spearman correlation with p-value verification).
* **Cross-Continental Sales:** Tested if sales trends across America, Asia, and Europe are statistically correlated.
* **A/B Testing Logic:** Compared sales performance between registered and non-registered users using appropriate statistical tests (T-test or Mann-Whitney U) depending on distribution normality.

### 4. Interactive Visualization (Tableau)
Created a high-impact, 2-page dashboard in Tableau Public to visualize:
* Sales dynamics and seasonality.
* Revenue breakdown by traffic channels and device types.
* Pivot tables for executive reporting.

---

##  Key Insights
* **Seasonality:** Identified specific time periods with significant sales spikes.
* **Device Efficiency:** Calculated the percentage of total sales coming from Mobile vs. Desktop.
* **User Value:** Statistically proved (or disproved) the difference in purchasing power between registered members and guests.

##  Project Structure
* [notebooks/](https://colab.research.google.com/drive/1tnlhFc79xK5RBLxKsKCbvbZrG0uMSRlP?usp=sharing) - Jupyter Notebook with Python code and statistical analysis.
* [tableau/](https://public.tableau.com/app/profile/mariia.korotnian4634/viz/Project1_17749440095570/Project1
) - Link to the interactive dashboard on Tableau Public.

---
**📊 Dashboard Link:** https://public.tableau.com/app/profile/mariia.korotnian4634/viz/Project1_17749440095570/Project1
