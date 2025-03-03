# ☕ Coffee Sales Analysis - Excel Dashboard Project  

## 📌 Project Overview  
The **Coffee Sales Analysis** project provides an in-depth sales performance analysis using **advanced Excel functions, Pivot Tables, and interactive Dashboards**. The objective is to transform raw transactional data into structured insights, enabling data-driven decision-making.  

This project leverages **lookup functions, conditional logic, data visualization, and dashboarding techniques** to uncover trends in coffee sales, identify top customers, and analyze sales performance across different countries.  

## 🎯 Objectives  
The primary goals of this project are:  
✅ **Data Cleaning & Preprocessing** – Organizing and structuring data for analysis  
✅ **Data Enrichment** – Using lookup functions to complete missing fields  
✅ **Sales Performance Analysis** – Evaluating trends across multiple dimensions  
✅ **Customer & Country Analysis** – Identifying top customers and geographical sales distribution  
✅ **Interactive Dashboard Creation** – Allowing dynamic exploration using slicers  

## 🏗️ Dataset & Structure  
This project consists of three datasets stored in an **Excel workbook**, structured as follows:  

### **1️⃣ Orders Data (Transactional Sales Data)**  
| Column Name       | Description |  
|------------------|-------------|  
| Order ID        | Unique identifier for each order |  
| Order Date      | Date of purchase |  
| Customer ID     | Unique identifier for each customer |  
| Product ID      | Identifier for the purchased coffee product |  
| Quantity        | Number of units purchased |  
| Customer Name   | Name of the customer (to be retrieved using lookup functions) |  
| Email          | Customer’s email (to be retrieved using lookup functions) |  
| Country        | Country of the customer (to be retrieved using lookup functions) |  
| Coffee Type    | Type of coffee purchased (to be retrieved using lookup functions) |  
| Roast Type     | Roast level of the coffee (to be retrieved using lookup functions) |  
| Size          | Package size of the coffee (to be retrieved using lookup functions) |  
| Unit Price    | Price per unit (to be retrieved using lookup functions) |  
| Sales         | Total sales amount (`Quantity × Unit Price`) |  

### **2️⃣ Customer Data**  
| Column Name       | Description |  
|------------------|-------------|  
| Customer ID     | Unique customer identifier |  
| Customer Name   | Full name of the customer |  
| Email          | Email address of the customer |  
| Phone Number   | Contact number |  
| Address Line 1 | Street address |  
| City          | City of residence |  
| Country       | Country of residence |  
| Postcode      | Postal code |  
| Loyalty Card  | Indicates if the customer has a loyalty membership |  

### **3️⃣ Product Data**  
| Column Name       | Description |  
|------------------|-------------|  
| Product ID      | Unique identifier for each coffee product |  
| Coffee Type    | Type of coffee (e.g., Espresso, Latte, Americano) |  
| Roast Type     | Roast level (Light, Medium, Dark) |  
| Size          | Package size (e.g., 250g, 500g, 1kg) |  
| Unit Price    | Price per unit |  
| Price per 100g | Standardized price metric for comparison |  
| Profit        | Profit margin per unit |  

---

## ⚡ Steps Involved  

### **🔹 Step 1: Data Preprocessing & Cleaning**  
✔️ Use **XLOOKUP & INDEX-MATCH** to fill missing details (`Customer Name`, `Email`, `Country`, `Coffee Type`, etc.)  
✔️ Use **Multiplication Formula** to calculate total sales per order  
✔️ Apply **Multiple IF functions** for conditional classifications  
✔️ Format **Dates & Numbers** for consistency  
✔️ Check for **Duplicate Entries** and remove inconsistencies  
✔️ Convert raw data into **structured Excel Tables** for better usability  

### **🔹 Step 2: Data Analysis & Reporting**  
✔️ Develop **Pivot Tables** to analyze key sales metrics  
✔️ Evaluate **Sales Over Time (2019, 2020, 2021)**  
✔️ Perform **Sales by Country** analysis to assess regional performance  
✔️ Identify **Top 5 Customers** based on total sales contribution  

### **🔹 Step 3: Building the Interactive Dashboard**  
✔️ Create visually appealing **Pivot Charts**  
✔️ Implement **Slicers & Timelines** for interactive filtering  
✔️ Allow data exploration based on **Roast Type, Coffee Size, & Loyalty Card Holders**  
✔️ Ensure dynamic **data source updating** for real-time insights  

---

## 📊 Key Insights & Findings  

### **📈 Sales Over Time (2019-2021)**  
- Trends in **total revenue** across three years  
- Identification of peak sales periods  

### **🌍 Sales by Country**  
- Breakdown of revenue by geographical location  
- Analysis of country-wise customer engagement  

### **🏅 Top 5 Customers**  
- High-value customers contributing the most to revenue  
- Insights into their purchase behavior  

### **📊 Interactive Dashboard**  
- Dynamic filtering options for in-depth analysis  
- One-click access to key performance metrics  

---

## 📂 Project Files  

📁 **Coffee_Sales_Dataset.xlsx** – The raw dataset used for analysis  
📁 **Coffee_Sales_Analysis_Report.xlsx** – The processed file with reports & dashboard  
📁 **README.md** – Project documentation  

---

## 🔧 Tools & Skills Used  
🟢 **Excel Functions** – XLOOKUP, INDEX-MATCH, IF formulas  
🟢 **Data Cleaning** – Handling missing values, formatting, duplicate removal  
🟢 **Pivot Tables & Pivot Charts** – For data summarization & visualization  
🟢 **Interactive Dashboard** – Using slicers & timelines for analysis  
🟢 **Number Formatting & Conditional Formatting** – For better report presentation  

---

## 🛠️ How to Use This Project  

1️⃣ **Download the project files** from this repository  
2️⃣ Open the **Coffee_Sales_Analysis_Report.xlsx** file  
3️⃣ Navigate through **Pivot Tables & Charts** for key insights  
4️⃣ Use **Slicers & Timelines** to filter data dynamically  
5️⃣ Analyze trends in **sales, top customers, and country-wise performance**  

---

## 📌 Future Improvements  
🚀 Add more **KPIs (Key Performance Indicators)** for deeper analysis  
🚀 Automate **data updates** using **Power Query**  
🚀 Expand to **monthly or seasonal trends** for granular insights  
🚀 Integrate with **Power BI** for advanced visualizations  

---

## 📜 Conclusion  
This **Coffee Sales Analysis project** provides **meaningful insights into business performance**, helping organizations optimize their sales strategies. With **Excel's powerful analytical tools**, businesses can track revenue, identify high-value customers, and make **data-driven decisions** with confidence.  

📊 **This project is ideal for those looking to enhance their data analysis skills using Excel.**  

---

