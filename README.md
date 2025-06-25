# Movie Revenue Data Analysis and Business Insights
## 🎥 Movie Revenue Analysis & Business Intelligence Project

**📊 Overview**

This project explores the business dynamics of the movie industry using data analytics, machine learning, and business intelligence tools. By integrating data from IMDb, TMDb, and Rotten Tomatoes, we built an end-to-end pipeline to analyze what makes a film financially successful.

The final deliverables include:

- A cleaned, unified dataset of 4000+ movies

- An interactive Power BI dashboard with dynamic slicers and KPIs

- ML models (Decision Tree & Random Forest) to predict box office success

- K-means clustering to segment movies into clear financial archetypes

**📌 Problem Statement**

The movie industry faces increasing uncertainty in predicting the commercial success of films before release. This project aims to identify key factors influencing box office performance using historical data and predictive analytics.

**🔧 Tools & Technologies**

- Python: Pandas, Scikit-learn, Seaborn, Matplotlib

- Power BI: Data modeling, DAX, dashboard creation

- SQL: SQLite for querying IMDb database

- Jupyter Notebook: Data preprocessing, EDA, modeling

- ML Models: Decision Tree, Random Forest

- Unsupervised Learning: K-means Clustering, PCA

**📈 Project Workflow**

1. **Data Collection**
   - Gathered data from IMDb, TMDb, Rotten Tomatoes (CSV, TSV, DB files)

2. **Data Cleaning & Preprocessing**
   - Standardized date formats and financial fields
   - Handled outliers, missing values, and multi-genre flags
   - Created derived financial metrics: ROI, profit, profit margin

3. **Exploratory Data Analysis (EDA)**
   - Analyzed profitability trends by genre, seasonality, and popularity
   - Created correlation heatmaps and feature distributions

4. **Machine Learning Models**
   - Converted ROI into binary success/failure labels
   - Trained Decision Tree and Random Forest models
   - Achieved 80% prediction accuracy with Random Forest
   - Plotted feature importance for business interpretability

5. **Clustering & Segmentation**
   - Applied K-means clustering (k=4, via elbow method)
   - Used PCA for 2D visualization of movie segments

6. **Power BI Dashboard**
   - Created interactive visualizations: revenue trends, genre-wise ROI, KPIs
   - Enabled dynamic filtering by year, genre, and budget tiers

**🎯 Key Business Insights**

- Genres with highest ROI: Horror, Animation, and Romance

- Optimal release months: May, June, July, and December

- Blockbusters demand massive budgets but deliver proportionally lower ROI than sleeper hits

- Identified 4 movie archetypes: Sleeper Hits, Blockbusters, Mid-tier Mainstream, and Underperformers

**📊 Deliverables**

- 📄 final_dataset.csv

- 📊 DSBI Dashboard.pbix

- 📒 DSBI_Project.ipynb (Python EDA & ML)



**📌 Conclusion**

This project demonstrated the power of combining data science, machine learning, and BI tools to derive actionable business insights in the entertainment industry. It highlighted how data-driven strategies can guide movie production, release timing, and marketing decisions to maximize commercial success.

**📚 References**

- IMDb Dataset

- Rotten Tomatoes

- TMDb Dataset
