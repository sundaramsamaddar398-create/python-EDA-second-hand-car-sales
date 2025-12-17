# python-EDA-second-hand-car-sales
End‑to‑end exploratory data analysis of used car listings using Pandas. Includes data ingestion, cleaning nulls/duplicates, anomaly detection, feature engineering, group‑wise queries, and visualizations (correlation, bar, scatter, box plots) to extract business insights on pricing and demand.

## 🚗 Used Car Price Analysis with Pandas
### 📌 Project Overview
This project performs end‑to‑end exploratory data analysis (EDA) on a real‑world dataset of used car listings. The workflow covers data ingestion, cleaning, anomaly detection, feature engineering, queries, and visualization to extract meaningful business insights about car pricing, demand, and resale trends.

### 📂 Dataset
- Source: car_prices.csv
- Attributes: selling price, brand, model year, condition, mileage, fuel type, location, color, interior, etc.
- Use Case: Market analysis, price prediction, demand‑supply insights.

### 🛠️ Technologies Used
- Python
- Pandas for data wrangling
- Matplotlib for visualization
- Jupyter Notebook in VS Code for analysis and documentation

### 📑 Tasks & Workflow
#### 1. Data Ingestion & Quality Profiling
- Loaded dataset into Pandas DataFrame.
- Inspected structure: rows, columns, data types.
- Profiled dataset: missing values, duplicates, anomalies.
- Applied cleaning strategies: imputation, duplicate removal, audit‑ready documentation.

#### 2. DataFrame Queries
- Calculated average, min, max selling price.
- Listed unique colors, brands, models.
- Filtered cars with price > $165,000.
- Found top 5 most frequently sold models.
- Computed average price by brand, minimum price by interior, highest odometer per year.
- Engineered new feature: car age (2025 − model year).
- Applied conditional queries (e.g., condition ≥ 48 & odometer > 90,000).
- Identified states with higher prices for newer cars.
- Value‑for‑money analysis: makes with lowest average price in top 20% condition.

#### 3. Data Visualization & Insights
- Correlation heatmap of numerical features.
- Scatter plot: average selling price by year → depreciation trend.
- Scatter plot: average selling price by odometer → inverse relationship.
- Bar chart: cars sold per state → top 3 selling states.
- Bar chart: average price by condition ranges (size 5).
- Bar chart: number of cars sold by condition ranges (size 10).
- Box plot: selling price distribution by color.
- Outliers identified and removed using group‑wise IQR filtering.
- Replotted for cleaner insights.

### 📊 Key Insights
- Neutral colors (black, white, silver) dominate sales and command higher median prices.
- Bright colors (yellow, lime, pink) cluster at lower price ranges.
- Mileage strongly influences resale value — higher odometer readings reduce price.
- Condition score is a strong predictor of price; excellent condition retains value.
- Certain states consistently show higher prices for newer cars.
- Outlier removal clarified distributions, preventing luxury models from distorting trends.

### 📌 Conclusion
This project demonstrates hands‑on proficiency in Pandas for EDA. It highlights skills in:
- Data cleaning & anomaly detection
- Feature engineering
- Group‑wise queries & aggregations
- Visualization & storytelling
- Audit‑ready documentation
