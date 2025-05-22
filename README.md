#  Sales Data Summary with SQLite, Pandas & Matplotlib

This project demonstrates how to analyze basic sales data stored in a **SQLite database** using **Python**, **SQL queries**, and **Matplotlib** for data visualization.

---

##  Project Structure

```
sales_summary/
├── sales_data.db                    # SQLite database with a 'sales' table
├── sales_analysis.py               # Python script or Jupyter notebook
├── total_revenue_by_product.png    # Chart 1
├── quantity_sold_by_product.png    # Chart 2
├── monthly_revenue_trend.png       # Chart 3
└── README.md
```

---

##  Tools & Libraries Used

- Python (3.x)
- sqlite3 (standard library)
- pandas
- matplotlib

---

##  What the Script Does

1. Connects to `sales_data.db` (SQLite).
2. Executes multiple SQL queries to summarize sales data:
   - Total quantity sold per product
   - Total revenue per product
   - Monthly revenue trends
   - Top 5 best-selling products
3. Displays query results using `print()` and pandas DataFrames.
4. Visualizes results using Matplotlib bar and line charts.
5. Saves all charts as `.png` images.

---

##  Charts Generated

- `total_revenue_by_product.png` – Bar chart of revenue by product
- `quantity_sold_by_product.png` – Bar chart of quantity sold by product
- `monthly_revenue_trend.png` – Line chart of revenue over months

---

##  How to Run

### 1. Install Requirements
```bash
pip install pandas matplotlib
```

### 2. Run the Script
```bash
python sales_analysis.py
```
Or run it in a Jupyter Notebook.

---
