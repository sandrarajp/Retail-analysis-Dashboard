
# 📊 Retail Performance Analysis Dashboard
![WhatsApp Image 2025-08-14 at 16 00 51_2e1b8932](https://github.com/user-attachments/assets/08236a9c-4a8d-480f-a678-ea28c6cee4e8)
  
![WhatsApp Image 2025-08-14 at 15 56 57_a8827006](https://github.com/user-attachments/assets/3beebcb2-42dd-4368-9215-2ed8a733bfaf)

![WhatsApp Image 2025-08-14 at 15 56 38_8e9a950c](https://github.com/user-attachments/assets/cbae1294-1085-4488-bc29-025f504fcf0d)

## 📌 Project Overview  
This project provides an **end-to-end retail analytics solution** using **Excel**, **Python**, and **Tableau**.  
It analyzes **sales performance, profit trends, delivery efficiency, and return rates**, helping stakeholders identify areas for growth and cost reduction.  

The dashboard is designed for **interactive exploration** with filters for **Year, Category, Segment, and State**.  

---

## 📂 Project Components  
### 1️⃣ **Excel** – *Retail Dashboard*  
- Created using Pivot Tables, Slicers, and Conditional Formatting.  
- KPI Cards: Total Sales, Total Profit, Avg Delivery Days, Return Rate.  
- Interactive charts for category breakdowns, monthly trends, and return analysis.  

📄 **File:** `Retail_Dashboard_Excel.xlsx`  

---

### 2️⃣ **Python** – *Retail Analytics EDA & Visualization*  
- Data cleaning & feature engineering:
  - Delivery Days calculation
  - Profit Margin computation
  - Return Rate calculation
- Insights generated:
  - Best/worst profit margin categories
  - Delivery speed impact on returns
  - State-wise return analysis
- Dashboard-style visualization using **Matplotlib** & **Seaborn** with **Power BI-like theme**.  

📄 **File:** `retail_analysis_python.ipynb`  

---

### 3️⃣ **Tableau** – *Interactive Dashboard v1*  
- **KPIs:**  
  - 📦 Total Sales  
  - 💰 Total Profit  
  - ⏱ Avg Delivery Days  
  - ↩ Return Rate  
- **Charts:**
  - Sales & Profit by Category → Sub-Category (drilldown)
  - Map of India by State (Sales heatmap)
  - Monthly trend: Sales & Profit (dual axis line chart)
  - Return Rate by ShipMode
- **Filters:** Year, Category, Segment, State  

📄 **File:** `Retail_Dashboard_Tableau.twbx`  

---

## 📊 Data Source  
- **File:** `Retail_Sales_Data.csv`  
- Columns:
  - `OrderDate` (Date)
  - `ShipDate` (Date)
  - `Category`, `Sub-Category`, `State`, `Segment` (Text)
  - `Sales`, `Profit` (Numeric)
  - `Returned` (0/1 flag)  

---

## 🚀 How to Run  
### **Excel**
1. Open `Retail_Dashboard_Excel.xlsx` in Microsoft Excel (2016+).
2. Use slicers to filter by Year, Category, Segment, State.

### **Python**
```bash
pip install pandas matplotlib seaborn numpy
jupyter notebook retail_analysis_python.ipynb

