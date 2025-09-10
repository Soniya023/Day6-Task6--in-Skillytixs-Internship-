# Day6-Task6--in-Skillytixs-Internship-
Generate sales summary reports using Python, SQLite &amp; Matplotlib

## Summary
This project demonstrates how to generate a sales summary from a small SQLite database using Python.  
It fetches total quantity sold and revenue per product using SQL, displays the results in a table, and visualizes revenue with a bar chart using Matplotlib.

## Tools Used
- Python (`sqlite3`, `pandas`, `matplotlib`)
- SQLite (built into Python)
- Jupyter Notebook or Python `.py` script

## Deliverables
- Python script / Jupyter Notebook that:
  - Connects to `sales_data.db`
  - Runs SQL query to calculate total quantity and revenue per product
  - Prints the results
  - Plots a bar chart for revenue

## Optional
- Save chart as image (`plt.savefig("sales_chart.png")`)
- Export results as CSV (`df.to_csv("sales_summary.csv", index=False)`)
