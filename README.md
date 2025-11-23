# 🛒 Retail Sales Analysis Project  
**End-to-End Data Analytics Project using Python, Power BI & SQL**

This project demonstrates a complete data analytics workflow, covering data cleaning, preprocessing, exploratory data analysis (EDA), visualization, and business insights generation.  
It is designed to showcase practical skills required for **Data Analyst**, **Business Analyst**, or **Power BI Analyst** roles.

---

## 📌 Project Objectives
- Clean and preprocess raw retail sales data  
- Perform exploratory data analysis to uncover patterns  
- Identify key business drivers such as revenue, profitability, and customer trends  
- Build interactive Power BI dashboards for decision-making  
- Document insights and create resume-ready outcomes  

---

## 📂 Project Structure

```
Retail-Sales-Analysis/
│
├── data/
│   ├── raw/                ← Uncleaned CSV file
│   └── processed/          ← Cleaned dataset after preprocessing
│
├── notebooks/
│   └── analysis.ipynb      ← Python-based cleaning & EDA
│
├── powerbi/
│   └── sales_dashboard.pbix ← Power BI dashboard file
│
├── reports/
│   └── visuals/            ← Exported charts & insights
│
└── README.md               ← Project documentation
```

---

## 🧹 1. Data Cleaning Workflow (Python)
The dataset is cleaned using:
- Handling missing values  
- Standardizing column names  
- Converting date formats  
- Removing duplicates  
- Creating new features like:
  - `Revenue = Quantity * Unit_Price`
  - `Order_Year`, `Order_Month`
  - Customer segmentation flags

Cleaned dataset is exported to:  
`data/processed/sales_clean.csv`

---

## 📊 2. Exploratory Data Analysis (EDA)
The notebook answers important business questions:

### **Key Insights:**
- **Total Revenue** and growth trend over months  
- **Top performing product categories**  
- **Customer purchase frequency & segments**  
- **Monthly sales seasonality**  
- **Best cities & regions by sales**  
- **High-value vs low-value customers**  
- **Profitability analysis by product**

### Visuals created:
- Revenue trend line chart  
- Category-wise sales bar chart  
- Customer segmentation histogram  
- Time-series decomposition  
- Correlation heatmap  
- Top 10 products by sales  

---

## 📊 3. Power BI Dashboard
A fully interactive dashboard containing:

### **Pages**
1. **Executive Summary**  
2. **Sales Overview**  
3. **Customer Insights**  
4. **Product Performance**  
5. **Region/City Comparison**

### **DAX Measures Used**
- `Total Sales`
- `Total Quantity`
- `Average Order Value`
- `Sales YoY %`
- `Customer Count`
- `Top Products (RankX)`
- `Monthly Sales Trend`
- `Running Total Sales`

---

## ▶️ How to Run the Project

### **Step 1 — Clone the Repo**
```
git clone https://github.com/yourusername/sales-analysis-project
```

### **Step 2 — Install Dependencies**
```
pip install -r requirements.txt
```

### **Step 3 — Run Jupyter Notebook**
```
jupyter notebook notebooks/analysis.ipynb
```

### **Step 4 — Open the Power BI Dashboard**
Open the `sales_dashboard.pbix` file in Power BI Desktop.

---

## 📸 Dashboard Preview

Below is a preview of the final Power BI dashboard:

![Retail Sales Dashboard](reports/dashboards_screenshots/dashboard.jpg)

---

## 📝 Final Summary (For Recruiters)
This project demonstrates skills in:
- Python (Pandas, NumPy, Matplotlib)
- SQL-like transformations
- Power BI dashboard development
- Data cleaning & preprocessing
- EDA & business insights generation
- Git/GitHub version control
- Communication of insights

---

## 📧 Contact
**Tony Antony**  
Data Analyst  
📍 Bangalore, India  
📧 tonyaj1100@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/tony-antony-data)  
🔗 [GitHub](https://github.com/tonyaj1100)



