
# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project exploring customer purchasing patterns, product performance, discount usage, subscriptions, and revenue using **Python, PostgreSQL, and Power BI**.

## 📌 Overview

The objective of this project is to analyze customer shopping behavior, identify meaningful patterns, and generate actionable business insights through data analysis and visualization.

## 📂 Dataset

The dataset contains customer shopping information, including:
- Customer demographics (age, gender)
- Product categories and purchased items
- Purchase amounts and review ratings
- Shipping types and discount usage
- Subscription status and previous purchases

## 🛠️ Tools & Technologies

| Tools | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Data visualization |
| Jupyter Notebook | EDA and data cleaning |
| PostgreSQL | Database management |
| SQL | Business analysis |
| Power BI | Interactive dashboard |
| Gamma | Project presentation |

## ⚙️ Project Workflow

1. **Data Loading:** Imported the dataset into Python using Pandas.
2. **EDA:** Explored data distributions, patterns, and relationships.
3. **Data Cleaning:** Handled missing values, standardized columns, and created new features.
4. **SQL Analysis:** Loaded cleaned data into PostgreSQL and performed 10 business-driven SQL analyses.
5. **Dashboard:** Built an interactive Power BI dashboard to visualize key metrics.
6. **Reporting:** Prepared a project report and presentation using Gamma.

## 🔍 SQL Analysis

Key business questions explored:

- Revenue by gender and age group.
- Discount usage and customer spending.
- Top-rated and most-purchased products.
- Average spending by shipping type.
- Subscription behavior and revenue comparison.
- Customer segmentation (New, Returning, Loyal).
- Repeat purchasing behavior.

**SQL Concepts:** Aggregations, Subqueries, CASE Statements, CTEs, and Window Functions.

## 📊 Dashboard

Developed an interactive Power BI dashboard to highlight customer behavior, revenue distribution, product performance, and purchasing patterns.

!([customer_behavior_analysis/Screenshot 2026-11-06 104151.png)](https://github.com/shatabdiss/Data-Analytics-Projects-/blob/main/customer_behavior_analysis/Screenshot%202026-11-06%20104151.png)

## 📈 Results & Insights

- Analyzed revenue contribution across customer segments.
- Identified highly rated and frequently purchased products.
- Explored discount usage and spending patterns.
- Examined subscription behavior among repeat customers.
- Identified customer segments and age-based revenue trends.

## 📁 Repository Structure

```text
customer_behavior_analysis/
│
├── data/
├── notebooks/
├── sql/
├── powerbi/
├── report/
├── presentation/
├── images/
└── README.md
```

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone <repository-url>
cd customer_behavior_analysis
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

**3. Launch Jupyter Notebook**
```bash
jupyter notebook
```

**4. Run the notebook**

Open the project notebook, load the dataset from the `data/` directory, and execute the cells sequentially.

**5. PostgreSQL & Power BI**

- Create the `customer_behavior` database in PostgreSQL.
- Configure your database connection.
- Run the SQL queries.
- Open the `.pbix` file in Power BI Desktop.

## 👩‍💻 Author

**Shatabdi Sarker**

🔗 [GitHub](https://github.com/shatabdiss)

💡 *Interested in Data Analytics, Data Science, and Machine Learning.*
