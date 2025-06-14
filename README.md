# 📈 Basic Sales Summary with SQLite and Python

## 🗂️ Project Overview

This project demonstrates how to use **SQLite**, **SQL queries**, **Python**, **pandas**, and **matplotlib** together to:
- Create a simple sales database.
- Query and summarize sales data using SQL inside Python.
- Analyze total quantities sold and total revenue by product.
- Visualize the sales summary as an easy-to-read bar chart.

This is a beginner-friendly example to practice **database handling, SQL aggregation, and data visualization in Python**.

## 📊 Dataset

A **tiny SQLite database (`sales_data.db`)** is created directly in the notebook/script.
The `sales` table contains:
| product | quantity | price |
|---------|----------|-------|
| Laptop  | 5        | 800   |
| Phone   | 10       | 300   |
| Tablet  | 4        | 400   |
| ...     | ...      | ...   |

## ⚙️ Tools & Libraries

- SQLite (Python built-in — no extra installation)
- SQL
- `sqlite3`, `pandas`, `matplotlib`
- Google Colab, Jupyter Notebook, or Python script

## 🚀 How to Run

1. Open `notebooks/sales_summary.ipynb` in Google Colab or locally.
2. Run each cell step-by-step.
3. The notebook will:
   - Create the database
   - Insert sample data
   - Query totals and revenue
   - Display a summary table and a bar chart
4. The chart can be saved to `output/sales_chart.png`.

## 📁 Repository Structure

```
basic-sales-summary/
├── data/
│   └── sales_data.db
├── notebooks/
│   └── sales_summary.ipynb
├── scripts/
│   └── sales_summary.py
├── output/
│   └── sales_chart.png
└── README.md
```

## ✅ Highlights

- SQL inside Python
- `SUM()` + `GROUP BY` examples
- pandas DataFrame from SQL
- Basic matplotlib plot

## 🎓 Learning Outcomes

- Create/populate SQLite DB programmatically
- Run aggregation queries
- Analyze with pandas
- Plot results with matplotlib

## 📜 License

Open source — for learning and practice.

## 🚀 Happy Analyzing!

