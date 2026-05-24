📌 Project Overview
This project performs a comprehensive end-to-end Exploratory Data Analysis (EDA) on a real-world e-commerce transactional dataset. The dataset contains 541,909 rows and 21 columns covering sales from multiple countries.
The goal is to uncover actionable business insights related to sales performance, product trends, customer behavior, and market opportunities — using Python's core data science libraries.

📂 Project Structure
ecommerce-sales-analysis/
│
├── ecommerce_analysis.ipynb   # Main Jupyter Notebook
├── requirements.txt           # Python dependencies
├── .gitignore                 # Files to ignore in git
├── README.md                  # Project documentation
│
└── images/                    # All charts and visualizations
    ├── monthly_sales.png
    ├── daily_trends.png
    ├── top_countries.png
    ├── best_selling_products.png
    ├── most_returned_products.png
    ├── high_revenue_products.png
    ├── top_customers.png
    ├── repeat_customers.png
    └── customer_lifetime_value.png

📊 Analysis Breakdown
1. 💰 Sales Analysis

Total Revenue — Overall revenue generated across all transactions
Monthly Sales Trends — Which months had the highest and lowest sales
Daily Trends — Peak days of the week for shopping activity
Top Countries by Revenue — Which countries contributed most to sales

2. 📦 Product Analysis

Best Selling Products — Top products by quantity sold
Most Returned Products — Products with highest return/cancellation rates
High Revenue Products — Products generating the most revenue

3. 👥 Customer Analysis

Top Customers — Customers who spent the most overall
Repeat Customers — Customers who made multiple purchases (loyalty indicator)
Customer Lifetime Value (CLV) — Estimated total value each customer brings

4. 💡 Business Insights

Which country generates the highest sales?
What are the peak shopping months?
What is the average basket size per transaction?


📈 Key Insights Found
InsightFindingTop Revenue CountryUnited Kingdom dominates overall salesPeak Shopping MonthNovember–December (holiday season)Best Selling ProductWHITE HANGING HEART T-LIGHT HOLDERAverage Basket Size~20 items per transactionMost Loyal CustomersSmall group drives majority of revenue (Pareto principle)High Return RateCertain low-cost items have disproportionately high returns

🛠️ Tech Stack
LibraryPurposePython 3.xCore programming languageNumPyNumerical computations and array operationsPandasData loading, cleaning, manipulationMatplotlibBase-level plotting and chart customizationSeabornStatistical visualizations and heatmapsJupyter NotebookInteractive development environment

🗂️ Dataset

Source: UCI Machine Learning Repository — Online Retail Dataset
Also available on: Kaggle — E-Commerce Data
Rows: 541,909
Columns: 21
Time Period: 2010 – 2011
Countries Covered: 38 countries


⚠️ The dataset CSV file is not included in this repository due to its large size. Please download it from the Kaggle link above.


⚙️ How to Run This Project
Step 1 — Clone the repository
bashgit clone https://github.com/YOUR_USERNAME/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis
Step 2 — Install dependencies
bashpip install -r requirements.txt
Step 3 — Download the dataset
Download data.csv from Kaggle and place it inside the project folder.
Step 4 — Open the Notebook
bashjupyter notebook ecommerce_analysis.ipynb
Step 5 — Run all cells
Go to Kernel → Restart & Run All

🔍 Data Cleaning Steps Performed

Removed rows with missing CustomerID values
Filtered out cancelled transactions (InvoiceNo starting with 'C')
Removed negative or zero Quantity and UnitPrice values
Converted InvoiceDate to datetime format
Created new feature: TotalPrice = Quantity × UnitPrice
Removed duplicate records


📚 Learnings from This Project

Handling and cleaning a large real-world dataset (500K+ rows)
Performing multi-dimensional EDA across sales, products, and customers
Building clear, business-relevant visualizations with Matplotlib & Seaborn
Understanding customer behavior patterns from transactional data
Applying the Pareto Principle (80/20 rule) to customer and product analysis


🙋‍♂️ About Me
[SHUBHAM MAURYA]
Aspiring Data Analyst | Python • Pandas • SQL • Data Visualization

🔗 LinkedIn: linkedin.com/in/your-profile
💻 GitHub: github.com/your-username
