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
| ![Total Sale By Region]) | ![Profit vs Total Sale] | ![Top Product By Total Sale] |
(image/Type_Plot_Combine.PNG)

---

### 📦 Folder Structure
