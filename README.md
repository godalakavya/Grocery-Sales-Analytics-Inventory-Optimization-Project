#  GROCERY SALES ANALYTICS & INVENTORY OPTIMIZATION

##  Power BI \| SQL \| Python \| Retail Analytics Project

------------------------------------------------------------------------
## Dashboard Images
<img width="1280" height="717" alt="image" src="https://github.com/user-attachments/assets/a1255482-6e47-4953-ab82-833e31e54c60" />
<img width="1187" height="675" alt="image" src="https://github.com/user-attachments/assets/6fd6ef9f-2932-4b99-8bbe-34a0dd4f3df8" />

##  Business Context

The grocery retail industry operates on thin margins and faces high
demand variability, especially for perishable goods. Inefficient
inventory planning often results in stockouts, revenue leakage, excess
holding costs, and product expiry.

This project transforms manual, reactive inventory management into a
forecast-driven, data-backed decision framework to improve operational
efficiency and profitability.

------------------------------------------------------------------------

##  Objective

To design and implement a data-driven inventory optimization solution
that:

-   Improves stock availability
-   Reduces expiry-related wastage
-   Enhances demand forecasting accuracy
-   Increases overall store profitability

------------------------------------------------------------------------

##  Problem Statement

-   Frequent stockouts of high-demand products led to lost sales and
    customer dissatisfaction.
-   Overstocking of perishable goods increased expiry losses and holding
    costs.
-   Manual reorder planning failed to account for seasonal and
    festival-driven demand fluctuations.
-   Limited centralized performance monitoring restricted proactive
    decision-making.

------------------------------------------------------------------------

##  Data Pipeline & Workflow

-   Integrated transactional sales, inventory logs, expiry tracking,
    discount data, store-level data, and festival indicators using SQL.
-   Performed data cleaning: removed duplicates, corrected
    inconsistencies, handled missing values, standardized categories,
    and validated time-series records.
-   Conducted Exploratory Data Analysis (EDA) to uncover seasonal
    trends, category performance, expiry concentration, and store-wise
    variability.
-   Designed a star-schema data model in Power BI for efficient
    multi-dimensional analysis.
-   Engineered advanced DAX measures:
    -   Total Sales
    -   Units Sold
    -   Average Selling Price
    -   Stockout Rate
    -   Wastage %
    -   Forecast Sales
    -   Forecast Accuracy
    -   Inventory Coverage Ratio
-   Developed a demand forecasting model in Python and validated it
    using MAE and MAPE.
-   Built a two-page interactive dashboard:
    -   Page 1: Sales & Inventory Performance Monitoring
    -   Page 2: Demand Forecasting & Inventory Optimization

------------------------------------------------------------------------

##  Analytical Framework

-   Descriptive Analytics -- Performance monitoring
-   Diagnostic Analytics -- Root cause analysis of stockouts & wastage
-   Predictive Analytics -- Time-series demand forecasting
-   Prescriptive Analytics -- Reorder optimization & stock balancing

------------------------------------------------------------------------

##  Key KPIs Defined

-   Stockout Rate = Missed Demand / Total Demand
-   Wastage % = Expired Inventory / Total Inventory
-   Forecast Accuracy = 1 − MAPE
-   Inventory Coverage = Current Stock / Forecast Demand
-   Average Selling Price = Total Sales / Units Sold

------------------------------------------------------------------------

##  Results & Business Impact

-   Reduced stockout rate from 12% to 4% using forecast-driven reorder
    optimization.
-   Decreased wastage by approximately 37% through improved stock
    balancing and expiry monitoring.
-   Increased revenue by approximately 18% due to improved product
    availability.
-   Generated an estimated ₹40 Lakhs annual revenue uplift.
-   Achieved ₹12 Lakhs in cost savings from reduced spoilage.
-   Improved customer satisfaction through consistent stock
    availability.

------------------------------------------------------------------------

##  Tools & Technologies

-   Power BI -- Data modeling, DAX, dashboard development
-   SQL -- Data extraction, joins, aggregations
-   Python (Jupyter Notebook) -- Data cleaning, forecasting, validation
-   Excel -- Data validation and preprocessing

------------------------------------------------------------------------

##  Future Enhancements

-   Integration with real-time inventory systems
-   Automated reorder implementation
-   Incorporation of external variables (supplier delays, weather
    impact)
-   Advanced forecasting using machine learning models

------------------------------------------------------------------------

##  Conclusion

This project demonstrates how retail analytics can move beyond reporting
into strategic decision support. By combining descriptive, predictive,
and prescriptive analytics, the solution successfully improved stock
availability, reduced wastage, and delivered measurable financial
impact.

------------------------------------------------------------------------

⭐ If you found this project valuable, feel free to connect or provide
feedback!
