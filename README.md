🛒 BigBasket Exploratory Data Analysis (EDA)
📌 Project Overview

This project analyzes the BigBasket Products Dataset using Exploratory Data Analysis (EDA).
The goal is to uncover insights about product pricing, discounts, brand performance, category distribution, ratings, and customer behavior.

This analysis is useful for understanding consumer patterns, pricing strategy, and business decision-making.

📂 Dataset Summary

The dataset includes:

Column	Description
product_name	Product name
brand	Brand of the item
category	Product category/subcategory
sub_category	Specific category segment
quantity	Product quantity/weight
rating	Customer rating (0–5)
reviews	Number of reviews
mrp	Original price
selling_price	Discounted/Final price
🎯 Objectives

Perform data cleaning & preprocessing

Handle missing values & inconsistent formatting

Analyze price trends

Compare brand performance

Study rating & review patterns

Understand category-wise distribution

Visualize insights through graphs

Provide business recommendations

🛠 Tech Stack Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🧹 Data Cleaning Performed

✔ Removed duplicates
✔ Treated missing values
✔ Cleaned quantity column (converted weights to numeric)
✔ Converted MRP & Selling Price to numeric
✔ Removed unnecessary symbols
✔ Added discount percentage column
✔ Cleaned brand & category text formatting

🔍 EDA Performed
1) Univariate Analysis

Category distribution

Brand distribution

Price distribution

Rating distribution

Review count distribution

2) Bivariate Analysis

Category vs Avg Price

Brand vs Avg Rating

MRP vs Selling Price

Rating vs Reviews

Discount % vs Rating

3) Multivariate Analysis

Correlation Heatmap

Scatter Plot: MRP vs Selling Price

Price–Rating–Reviews relationship

📊 Visualizations Used

Countplots

Bar charts

Boxplots

Histograms

Heatmap

Scatter plots

Pie charts (if used)

All major insights are supported with clear visualizations.

💡 Key Insights

📌 Grocery staples and household items dominate the dataset
📌 Categories like Beverages & Snacks have the highest variety
📌 Some brands have high MRP but average ratings
📌 Higher discount does NOT always mean better rating
📌 Products priced between ₹100–₹300 get the most reviews
📌 Rating distribution shows most products rated between 3.5–4.5 stars
📌 Many products have very few reviews → ratings not always reliable
📌 Significant price variation exists in the Beauty & Gourmet categories

🧠 Business Recommendations

✔ Promote top-rated categories more
✔ Re-evaluate pricing strategy of high-MRP low-rating brands
✔ Boost mid-range (₹100–₹300) products—they drive most engagement
✔ Increase verified customer reviews
✔ Offer discounts on low-demand categories
✔ Monitor categories with high price variation
✔ Strengthen marketing of high-rating, high-demand brands

📁 Project Structure
BigBasket_EDA_Project/
│
├── bigbasket_dataset.csv
├── BigBasket_EDA.ipynb
├── README.md
└── images/graphs...

👨‍💻 Author

Vishu Deshwal
Data Analyst | Python | Pandas 
