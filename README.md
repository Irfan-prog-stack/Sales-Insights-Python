# 🧠 Sales Insights using Python

### 📊 Project Overview  
This project analyzes electronic sales data using **Python (pandas, matplotlib, seaborn)** to uncover key business insights.  
It demonstrates how raw data can be cleaned, transformed, and visualized before being connected to a BI tool such as Power BI.

---

### 🎯 Objectives
- Clean and preprocess raw sales data.
- Analyze sales performance by product, region, and month.
- Identify top-performing products and profit trends.
- Prepare a clean dataset ready for dashboard integration.

---

### 🧩 Dataset Information
- **Source:** Simulated electronic sales data  
- **Rows:** ~1,000 transactions  
- **Key columns:**
  - `OrderID`
  - `Product`
  - `Quantity`
  - `Price`
  - `TotalSale`
  - `Region`
  - `Month_Name`

---

### ⚙️ Tools & Libraries
| Category | Tools |
|-----------|--------|
| Data Cleaning | Python, pandas |
| Visualization | matplotlib, seaborn |
| Environment | Jupyter Notebook |
| Export | CSV (ready for Power BI) |

---

### 🔍 Process Workflow
1. **Data Cleaning (`data_cleaning.ipynb`):**  
   - Removed missing & duplicate records  
   - Fixed inconsistent column names  
   - Added new metric `TotalSale = Quantity × Price`

2. **Data Analysis (`sales_analysis.ipynb`):**  
   - Sales trend by month  
   - Profit vs discount relationship  
   - Top 5 products by total sale

3. **Visualization (`visualization_demo.ipynb`):**  
   - Created exploratory plots  
   - Exported results as `.png` for reporting  

4. **Exported for BI Tools:**  
   - Final cleaned dataset: `product_summary.csv`

---

### 📈 Example Visuals
| Sales Trend | Profit vs Discount | Top Products |
|--------------|--------------------|---------------|
| ![Sales Trend](image/sales_trend_plot.png) | ![Profit vs Total Sale](image/profit_vs_totalsale.png) | ![Top Products](image/top_product_sales.png) |

---

### 📦 Folder Structure

data/ → Raw & cleaned CSV files
notebooks/ → Jupyter notebooks for each stage
images/ → Generated visualizations
README.md → Project summary
requirements.txt → Python dependencies

---

### 🚀 How to Run This Project
1. Clone this repository:
   ```bash
   git clone https://github.com/Irfan-prog-stack/Sales-Insights-Python.git

2. Navigate into the folder:
   cd Sales-Insights-Python
   
4. Install dependencies:
   pip install -r requirements.txt

5. Open the Jupyter notebook:
   jupyter notebook notebooks/sales_analysis.ipynb

---

💡 Key Learnings

- Hands-on experience with data wrangling using pandas
- Generating business insights programmatically
- Creating analysis-ready data for BI tools
- Building clean, reproducible data pipelines

---

👤 Author

Irfan Arifin
📍 Cyberjaya, Malaysia
📧 irfanarifin1794@gmail.com | www.linkedin.com/in/irfan-arifin-9206a922b

