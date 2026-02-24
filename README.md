# 🛍️ Customer Shopping Behavior – Retail Data Analytics

_Analyzing customer purchasing patterns and shopping behavior to support data-driven business decisions using SQL, Python, and Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#key-findings">Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project delivers an end-to-end data analytics workflow on customer shopping behavior data. A complete pipeline was built using SQL for querying and analysis, Python for EDA and data cleaning, and Power BI for interactive visualization — transforming raw retail data into actionable business insights.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Understanding customer behavior is critical for retail growth and strategy. This project aims to:
- Identify top-performing product categories and customer segments
- Analyze customer spending patterns and purchasing frequency
- Uncover trends that drive revenue and customer retention
- Support data-driven decisions for marketing and inventory planning

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- **File:** `data/customer_shopping_behavior.csv`
- Contains customer transaction records including product categories, purchase amounts, demographics, and shopping frequency
- Data was cleaned and preprocessed in Python before SQL analysis

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- **Python** (Pandas, Matplotlib, Seaborn) – EDA, data cleaning, visualization
- **MySQL** – SQL queries and deeper data analysis
- **Power BI** – Interactive dashboard and business reporting
- **Jupyter Notebook** – Python analysis environment
- **GitHub** – Version control and project sharing

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
customer-behavior-analysis-python-sql-powerbi/
│
├── README.md
│
├── assets/                        # Supporting images
│   └── dashbaord.PNG
│
├── data/                          # Raw dataset
│   └── customer_shopping_behavior.csv
│
├── notebooks/                     # Jupyter notebooks
│   └── customer_shopping_analysis_eda_python.ipynb
│
├── dashboard/                     # Power BI dashboard files
│   ├── customer_behavior_powerbi.pbix
│   └── customer_behavior_powerbi_dashboard.pdf
│
├── reports/                       # Final presentation
│   └── Customer-Shopping-Behavior-Analysis-Presentation.pdf
│
└── sql/                           # SQL analysis scripts
    └── customer_behavior_sql.sql
```

---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Handled missing values and null records
- Removed duplicate transactions
- Standardized data types across columns
- Filtered out invalid or inconsistent entries
- Prepared clean dataset for SQL import and Power BI connection

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Distribution Analysis:**
- Explored customer age groups, gender distribution, and purchase frequency
- Identified seasonal trends and peak shopping periods

**Spending Patterns:**
- Analyzed average order values across categories
- Identified high-value customer segments

**Correlation Analysis:**
- Relationship between customer demographics and spending behavior
- Category performance vs. purchase frequency

---

<h2><a class="anchor" id="key-findings"></a>Key Findings</h2>

1. **Top Categories** – Identified highest revenue-generating product categories
2. **Customer Segments** – Key demographic groups driving the majority of sales
3. **Spending Trends** – Seasonal and frequency-based purchasing patterns uncovered
4. **SQL Insights** – Deep-dive queries revealed hidden patterns in transaction data
5. **Business Opportunities** – Identified underperforming segments with growth potential

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

The Power BI dashboard provides:
- Customer purchasing trends over time
- Category-wise sales and revenue breakdown
- Spending behavior by demographic segments
- Key performance metrics and KPIs

![Customer Behavior Dashboard](assets/dashbaord.PNG)

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. **Clone the repository:**
```bash
git clone https://github.com/shubham-rajendra-patil/customer-behavior-analysis-python-sql-powerbi.git
```

2. **Install required Python libraries:**
```bash
pip install pandas numpy matplotlib seaborn
```

3. **Run Python EDA:**
   - Open `notebooks/customer_shopping_analysis_eda_python.ipynb`
   - Run all cells to perform EDA and data cleaning

4. **Run SQL Analysis:**
   - Import `data/customer_shopping_behavior.csv` into MySQL
   - Execute queries from `sql/customer_behavior_sql.sql`

5. **Open Power BI Dashboard:**
   - Open `dashboard/customer_behavior_powerbi.pbix` in Power BI Desktop
   - Refresh data connections if required

6. **View Report & Presentation:**
   - `reports/Customer-Shopping-Behavior-Analysis-Presentation.pdf`
   - `dashboard/customer_behavior_powerbi_dashboard.pdf`

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Focus marketing efforts on top-spending customer segments
- Promote underperforming but high-potential product categories
- Leverage seasonal trends for targeted campaigns
- Use purchase frequency insights to build loyalty programs
- Apply demographic insights to personalize customer experience

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Shubham Rajendra Patil**

[![GitHub](https://img.shields.io/badge/GitHub-shubham--rajendra--patil-181717?style=flat&logo=github)](https://github.com/shubham-rajendra-patil)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/shubham-rajendra-patil)

---
