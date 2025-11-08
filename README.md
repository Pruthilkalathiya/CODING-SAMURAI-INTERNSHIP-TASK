# 🧾 Sales Data Analysis  

## 📌 Project Overview  
This project is part of my **Data Science Internship at Coding Samurai**.  
The objective of this project is to analyze a small retail sales dataset using Python and perform **basic data analytics** — including total sales calculation, best-selling products identification, and visualizing results through charts.  

---

## 🎯 Goals  
- Perform **data cleaning** and **basic calculations** on sales data  
- Compute total sales and sales per product  
- Create **bar charts** and **pie charts** to visualize data  
- Gain understanding of basic data-analytics workflow  

---

## 🧩 Technologies Used  
| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Programming language |
| **Pandas** | Data handling and analysis |
| **Matplotlib** | Graph plotting |
| **Seaborn** | Attractive statistical visuals |
| **Google Colab / Jupyter Notebook** | Interactive environment |

---

## 📂 Dataset Description  
A simple CSV file (`sales_data.csv`) is created within the notebook.  

| Column | Description |
|---------|--------------|
| **Date** | Transaction date |
| **Product** | Product name |
| **Quantity** | Number of units sold |
| **Price** | Unit price of the product |
| **Total** | Computed column (`Quantity × Price`) |

Example data:

| Date | Product | Quantity | Price |
|------|----------|-----------|-------|
| 2024-01-01 | Apple | 10 | 5 |
| 2024-01-02 | Banana | 15 | 3 |
| 2024-01-03 | Mango | 8 | 6 |

---

## ⚙️ Steps Followed  

1. **Import Libraries**  
   ```python
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns
