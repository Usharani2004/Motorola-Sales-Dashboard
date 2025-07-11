# 📊 DAX Measures – Motorola Sales Dashboard

This file contains all the calculated DAX measures used in the Power BI dashboard for Motorola mobile sales analysis.

---

## 🧠 Key Measures

### 🧮 **Total Sales**
```DAX
Total Sales = SUMX(Sales_Data,Sales_Data[Units Sold]*Sales_Data[Price Per Unit]) 
```

### 📦 **Total Quantity**
```DAX
Total Quantity = SUM(Sales_Data[Units Sold])
```

### 💳 **Transactions**
```DAX
Transactions = COUNTROWS(Sales_Data)
```

### 📊 **Average Sales**
```DAX
Average = AVERAGE(Sales_Data[Price Per Unit])
```






