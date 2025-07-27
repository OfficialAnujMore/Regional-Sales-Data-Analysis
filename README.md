# 📊 Regional Sales Data Analysis

This project analyzes multi-year sales data (2014–2018) to uncover insights on regional performance, customer behavior, and product profitability. It leverages real-world business data and applies data wrangling, visualization, and analysis techniques using Python and Power BI.

---

## 📁 Dataset Overview
**Google Colab link:** https://colab.research.google.com/drive/1yVgetcQQthyWoQe3cRYRnK4q36Qohgk4

The dataset comes from a fictional business and includes detailed information about:

- **Sales Orders**: Order date, channel, region, quantity, pricing, and cost.
- **Customers**: Customer IDs and names.
- **Products**: Product IDs and descriptions.
- **Regions**: City and county metadata including population, income, and area codes.
- **State Regions**: U.S. state-to-region mappings (e.g., West, South).
- **2017 Budgets**: Budget allocations per product for 2017.

> **File Used:** `Regional Sales Dataset.xlsx`

---

## 🧠 Key Objectives

- Identify high-performing regions and products.
- Analyze sales and profit trends over time.
- Evaluate customer segments and sales channels.
- Compare actual performance with 2017 product budgets.
- Build an interactive dashboard for business users.

---

## 🔍 Analysis Workflow

1. **Data Loading & Inspection**  
   Load and explore each sheet using `pandas`.

2. **Data Cleaning**  
   Standardize columns, handle missing values, and convert data types.

3. **Data Merging**  
   Combine sales data with customer, product, and regional information.

4. **Exploratory Data Analysis (EDA)**  
   Use `matplotlib` and `seaborn` for:
   - Sales by region and year
   - Profit margins per product
   - Channel-wise performance
   - Customer segmentation

5. **Budget vs Actual (2017)**  
   Compare product-wise 2017 sales with provided budgets.

6. **Dashboarding in Power BI**  
   An interactive dashboard was built to allow business stakeholders to:
   - Filter by region, product, or sales channel
   - Track monthly revenue and profit trends
   - Visualize budget vs actual comparisons
   - Identify high-value customers and product lines

---

## 📌 Key Insights (Example)

- Certain regions consistently outperform others in both revenue and profit.
- A handful of products contribute to a majority of revenue.
- Export and wholesale channels have distinct profitability patterns.
- Several products underperform relative to their 2017 budgets.
- Power BI dashboard enables quick decision-making with interactive visualizations.

---

## 🛠️ Tech Stack

- **Python** (pandas, numpy, matplotlib, seaborn)
- **Jupyter Notebook**
- **Google Colab** (for data access from Google Drive)
- **Power BI** (for dashboarding and storytelling)
- **Excel** (structured input data)

---

## 🚀 How to Run

1. Clone this repository.
2. Upload `Regional Sales Dataset.xlsx` to your working directory or Google Drive.
3. Open and run `Regional Sales Data Analysis.ipynb` in Jupyter or Google Colab.
4. Open `Regional Sales Dashboard.pbix` (if shared) in Power BI Desktop to explore the interactive dashboard.

---

## 📂 File Structure

