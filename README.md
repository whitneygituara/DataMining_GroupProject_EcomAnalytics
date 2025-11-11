🛍️ DSA2040A_DataMining_EcomAnalytics
Uncovering Hidden Patterns in Brazil’s E-Commerce World 🇧🇷
🌟 Project Overview

Welcome to our end-to-end data mining adventure!
In this project, we’ll dive deep into the Brazilian E-Commerce Public Dataset by Olist, exploring how real customers shop, how sellers perform, and what drives customer satisfaction in Brazil’s growing online marketplace.

Our mission is to transform messy, real-world data into actionable insights — moving through every stage of the pipeline:
ETL → EDA → Data Mining → Insights & Storytelling.

We aim to answer real business questions, build machine learning models, and visualize insights that could help an e-commerce platform like Olist make smarter, data-driven decisions. 💡

🎯 Objectives & Research Questions

Our analysis is guided by key questions that reflect real business challenges:

👩‍💻 Customer Insights

Who are Olist’s most valuable customers?

Which regions in Brazil drive the most sales and revenue?

Can we segment customers based on their purchase frequency or spending?

📦 Product & Sales Analysis

Which product categories are the top performers?

How does seasonality (e.g., holidays) affect order volume?

What are the most preferred payment methods and how do they affect purchase size?

⭐ Customer Experience

What factors influence review scores?

Do late deliveries lead to lower satisfaction?

Are there correlations between order value, payment type, and review ratings?

🧠 Predictive & Pattern Discovery

Can we predict customer satisfaction (high vs low review)?

Which products are frequently bought together (market basket analysis)?

🧾 Dataset Description

📚 Source: Brazilian E-Commerce Public Dataset by Olist (Kaggle)

📊 Data Period: 2016–2018
📦 Files Included:

File	Description
olist_orders_dataset.csv	Order details and delivery statuses
olist_order_items_dataset.csv	Products sold per order
olist_products_dataset.csv	Product category metadata
olist_customers_dataset.csv	Customer info (state, city, ID)
olist_order_payments_dataset.csv	Payment methods and amounts
olist_order_reviews_dataset.csv	Customer review scores and comments
olist_sellers_dataset.csv	Seller info and location
olist_geolocation_dataset.csv	Latitude/longitude per ZIP code

🧹 The dataset is “beautifully messy” — it includes missing values, inconsistent dates, and duplicated records.
That gives us the perfect chance to showcase our ETL and cleaning skills!

🔧 Methodology & Approach
🔢 Phase	📝 Description	🧰 Tools & Techniques
1️⃣ Extract & Transform (ETL)	Import, clean, and merge raw Olist tables. Handle nulls, outliers, duplicates, and feature engineering (delivery delay, profit margin, etc.).	Python 🐍 (Pandas, NumPy)
2️⃣ Exploratory Data Analysis (EDA)	Visualize and summarize sales trends, distributions, and correlations.	Matplotlib, Seaborn, Plotly
3️⃣ Data Mining & Modeling	Apply clustering (K-Means), classification (Decision Tree / Logistic Regression), and association rules (Apriori).	scikit-learn, mlxtend
4️⃣ Insights & Storytelling	Build an interactive dashboard and extract actionable insights for business users.	Plotly Dash / Power BI / Jupyter
5️⃣ Reporting & Presentation	Summarize findings, challenges, and insights in an executive summary and presentation.	PDF Report, PowerPoint Slides
📂 Repository Structure
DSA2040A_DataMining_EcomAnalytics/
├── data/
│   ├── raw/                # Original Olist CSV files
│   ├── transformed/        # Cleaned and merged datasets
│   └── final/              # Ready-to-analyze datasets
├── notebooks/
│   ├── 1_extract_transform.ipynb
│   ├── 2_exploratory_analysis.ipynb
│   ├── 3_data_mining.ipynb
│   └── 4_insights_dashboard.ipynb
├── report/
│   ├── executive_summary.pdf
│   └── presentation.pptx
├── requirements.txt
├── .gitignore
└── README.md

👥 Team Members & Roles
🧑‍💻 Name	🎓 Role	🔍 Responsibilities
[Member 1]	ETL Lead	Data extraction, cleaning, transformation
[Member 2]	Data Analyst	EDA, visualization, and summary stats
[Member 3]	Data Miner / Modeler	Clustering, classification, pattern mining
[Member 4]	Reporter / Presenter	Dashboard creation, executive summary, presentation
All Members	Collaborators	Minimum 3 commits each + notebook comments
🧰 Tools & Technologies

🖥️ Programming: Python (Pandas, NumPy, scikit-learn)
📊 Visualization: Seaborn, Matplotlib, Plotly, Power BI
🧠 Machine Learning: K-Means, Logistic Regression, Decision Tree, Apriori
📁 Version Control: Git & GitHub (team workflow)
🧾 Reporting: Jupyter Notebooks, PDF, PowerPoint

🚀 Expected Outcomes

By the end of this project, we’ll have:
✅ A clean and enriched dataset ready for mining
📈 A detailed exploratory analysis with visuals
🤖 Machine learning models for clustering and prediction
🛍️ Actionable business insights for Olist’s growth
🎨 A mini insights dashboard for storytelling

Ultimately, this project demonstrates how data science transforms raw transactions into strategic intelligence — one dataset at a time. 🔥
