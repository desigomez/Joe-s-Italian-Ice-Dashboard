Italian Ice Sales Analytics & ETL Pipeline (Joe’s Italian Ice – Anaheim, CA)

📌 Project Overview
This project is an end-to-end analytics and ETL pipeline built to support operational and sales decision-making for Joe’s Italian Ice, a small business with high product variability and demand sensitivity.
Using real business data—including sales, flavor production, weather, and special events—I designed a data pipeline that transforms raw CSV files into analytics-ready datasets and delivers insights through Power BI dashboards with automated refresh.

🎯 Business Problem
Joe’s Italian Ice needed better visibility into:

* Which flavors were over or under produced
* How weather impacted daily sales
* Where product waste was occurring
* How quickly leadership could access sales insights
* Manual reporting was time-consuming and limited the ability to react to demand changes.

Objective:
* Create a scalable analytics solution that improves forecasting, reduces waste, and accelerates reporting.

🛠️ Tools & Technologies
* Python (Pandas, NumPy)
* SQL
* Amazon S3
* Power BI
* CSV based data ingestion

🔄 ETL Pipeline Overview
1. Extract

Ingested raw CSV files containing:
* Daily sales transactions
* Flavor production quantities
* Product usage and inventory
* Weather data (high/low temperatures)
* Special event records
2. Transform
* Cleaned and standardized raw datasets using Python
* Handled missing values, inconsistent formats, and duplicates
* Created analytical tables and KPIs including:
* Usage efficiency by flavor
* Flavor demand trends
* Temperature related sales patterns
* Daily and weekly sales aggregates
3. Load
* Uploaded transformed datasets to Amazon S3
* Connected S3 datasets to Power BI as the reporting layer
* Enabled automated refresh for ongoing analysis

📊 Dashboard & Analytics

The Power BI dashboard provides:
* Daily and monthly sales trends
* Flavor level demand vs production comparisons
* Weather correlation with revenue
* KPI tracking for operational efficiency

The dashboard is actively maintained to support ongoing business decisions.

📈 Business Impact

📉 15% reduction in product waste through improved production alignment

📊 10% improvement in flavor availability accuracy based on demand trends

⚡ 20% faster reporting turnaround for daily sales analysis

These insights enabled leadership to respond faster to demand changes and optimize production planning.

