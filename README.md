# Power-BI-Airbnb-Report
<img width="983" height="552" alt="Airbnb Report " src="https://github.com/user-attachments/assets/f3988c52-3849-40d9-9d42-f3e7ccec513d" />

This project is a comprehensive **Power BI Dashboard** that provides an in-depth, data-driven analysis of the Airbnb market across key New York City neighborhoods. The goal is to analyze and visualize rental performance, host distribution, and complex pricing and review trends to deliver actionable business intelligence for hosts, investors, and market analysts.

---

## 📊 Key Project Metrics

The dashboard is built on a rich dataset, summarizing the following high-level performance indicators for the NYC market:

* **Avg. Reviews per Month:** **1.37**
* **Total Hosts:** **37.36K**
* **Total Neighbourhoods:** **221**

---

## 📈 Data Insights & Visualization

The dashboard provides the following granular insights, enabling users to drill down into specific trends:

* **Total Bookings By Neighbourhood Group:**
    * **Manhattan** and **Brooklyn** are the dominant markets, responsible for the vast majority of bookings, approximately **22K** and **20K**, respectively.
    * **Queens** and **Bronx** follow with significantly lower volumes (approx. **6K** and **1K**).

* **Total Reviews by Month (Seasonality):**
    * The data clearly indicates a strong seasonal demand, with **Total Reviews** peaking during the summer months of **June** and **August** (both at approximately **20K** reviews).
    * Review volume drops off sharply in the last quarter of the year.

* **Average Price by Neighbourhood (Top 5):**
    * The most expensive neighbourhoods are **Fort Wadsworth** ($\$700.00$), **Woodrow** (approx. $\$590$), and **Tribeca** ($\$490.64$), indicating pockets of luxury or unique listings.

* **Total Neighbourhoods by Group (Distribution):**
    * The geographical distribution of listings is highest in **Manhattan (44.32%)** and **Brooklyn (41.16%)**, which together account for over 85% of all neighborhoods represented in the dataset.

* **Avg. Price by Neighbourhood Group and Room type:**
    * The highest average price point is for **Entire home/apt** in **Brooklyn** at **\$1,701.424**.
    * Conversely, **Shared rooms** consistently represent the lowest price category across all neighbourhood groups, often significantly less than $\$10$.

* **Avg. Reviews by Neighbourhood Group and Room type:**
    * Listings in **Staten Island** and **Queens** show the highest average reviews per month for **Entire home/apt** (2.07 and 1.95, respectively), suggesting high engagement or turnover in these areas.

* **Top 10 Hosts by Total Reviews:**
    * The top three hosts by total reviews are **Maya** (approx. 2.2K), **Danielle** (approx. 2.0K), and **Yasu & Akiko** (approx. 2.0K), highlighting the scale and success of these high-performing hosts.

---

## 💾 Data Source & Preparation

**Data Source:**
The data is sourced from a public Airbnb listings dataset (commonly found on platforms like Kaggle or Inside Airbnb) for the New York City region.

**ETL (Extract, Transform, Load) Process:**
The data was thoroughly processed using the **Power Query Editor** (M Language) in Power BI Desktop to ensure accuracy and usability:

* **Data Cleaning:** Handled null and missing values in critical columns such as pricing, reviews, and host information.
* **Data Typing:** Ensured correct data types, particularly standardizing date formats for trend analysis and converting the `price` column to a numeric/currency format.
* **Column Creation:** Created calculated columns where necessary to support key metrics and visualizations.

---

## 🛠️ Tools and Libraries

* **Power BI Desktop:** Core application used for dashboard design, data modeling, and visualization.
* **Power Query (M Language):** Used for advanced data extraction, cleaning, and transformation processes.
* **DAX (Data Analysis Expressions):** Utilized to create custom measures (like Averages and Aggregations) and calculated columns for complex filtering and metric computations.

---

## 🚀 Future Enhancements
* Implementing **What-If** parameter analysis for dynamic price forecasting.
* Integrating geospatial data for interactive map visualizations.
* Analyzing host response times and their correlation with review scores.
