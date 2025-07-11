# Motorola-Sales-Dashboard
Power BI dashboard analyzing Motorola mobile sales data

# 📊 Motorola Sales Dashboard – Power BI Project

This project is a visual dashboard built in Microsoft Power BI to analyze Motorola mobile sales data. It provides insights into sales performance, customer behavior, and transaction trends using interactive visuals, filters, and DAX calculations.

---

## 📁 Files Included

- `Motorola dashboard.pbix` – Power BI dashboard file  
- `Mobile Sales Data.xlsx` – Raw sales data used in the report   
- `All files.zip` – Complete project folder with PBIX, Excel, and supporting assets  

---

## 🧩 Dashboard Elements

### ✅ Layout & Features
- Used a **4-grid layout** for clean alignment of visuals  
- Included visuals like:
  - Line chart  
  - Bar chart  
  - Pie chart  
  - Column chart  
  - Map  
  - Funnel chart  
  - Table (with calculated KPIs)  
  - Slicers (for filtering by mobile model and month)  

---

### 🔹 Summary Metrics (KPI Cards)
- **Total Sales**: ₹769M  
- **Total Quantity**: 19K units  
- **Transactions**: 4K  
- **Average Sales/Transaction**: ₹40K  

---

### 🔹 Filters Used
- **Mobile Model** slicer (e.g., iPhone SE, OnePlus Nord, etc.)  
- **Month-wise** filter (January to December)  

---

## 📈 Visuals & Charts

### 🗺️ Total Sales by City (Map)
- Key cities: Mumbai, Delhi, Bangalore, Lucknow, Chennai, Hyderabad, Coimbatore, Kolkata, etc.  
- Bubble size indicates total sales value per city  

### 📊 Total Quantity by Month (Line Chart)
- Example:  
  - Jan: 1672  
  - Feb: 1451  
  - Dec: 1609  

### ⭐ Customer Ratings (Funnel Chart)
- 5 Stars: 311  
- 4 Stars: 185  
- 3 Stars: 137  
- 2 Stars: 119  
- 1 Star: 67  

### 💳 Transactions by Payment Method (Pie Chart)
- Debit Card: 25.89%  
- Credit Card: 25.03%  
- UPI: 26.25%  
- Cash: 22.83%  

### 📱 Total Sales by Mobile Model (Bar Chart)
- iPhone SE: ₹60M  
- OnePlus Nord: ₹58M  
- Galaxy Note: ₹56M  

### 📅 Total Sales by Day Name (Line Chart)
- Saturday: ₹110M  
- Sunday: ₹111M  
- Friday: ₹114M  
- Thursday: ₹107M  
- Wednesday: ₹106M  

### 📋 Summary Table (Brand-wise)
| Brand   | Total Sales | Total Quantity | Transactions |
|---------|--------------|----------------|--------------|
| Apple   | ₹1616M       | 3932           | 783          |
| OnePlus | ₹1537M       | 3830           | 768          |
| Samsung | ₹1600M       | 3923           | 775          |
| Vivo    | ₹1500M       | 3801           | 766          |
| Xiaomi  | ₹1437M       | 3664           | 743          |

- **Total Sales**: ₹7692M  
- **Total Quantity**: 19,150 units  
- **Transactions**: 3835  

---

## 🔧 Tools & Technologies Used

- **Power BI Desktop**  
- **Microsoft Excel**  
- **Power Query Editor** for data transformation  
- **DAX** for calculated measures  
- Interactive visuals: slicers, charts, maps, and tables  

---

## 🔄 Data Transformation (Power Query)

Transformations done before loading data:

- Merged `Day`, `Month`, `Year` into a single `Date` column  
- Created `Day Name` column
 
📄 For all calculated DAX measures used in the report, see [DAX_Measures.md](./DAX_Measures.md)

