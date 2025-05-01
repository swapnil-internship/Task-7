
# Task 7: Basic Sales Summary from SQLite Database

## Objective
Use SQL inside Python to pull simple sales info (like total quantity sold and total revenue), and display it using basic print statements and a simple bar chart.

## Tools Used
- Python (with `sqlite3`, `pandas`, `matplotlib`)
- SQLite (built-in with Python)
- Jupyter Notebook

## Files Included
- `sales_summary_task7.ipynb`: Jupyter Notebook containing all code for connecting to SQLite, querying sales data, and visualizing results.
- `sales_data.db`: SQLite database file created automatically when running the notebook.
- `sales_chart.png`: Bar chart output showing revenue per product (saved by the notebook).

## Steps Performed
1. **Connect to SQLite Database**  
   Create or connect to `sales_data.db`.

2. **Create Sales Table and Insert Data**  
   A table named `sales` is created and populated with sample data (products, quantities, prices).

3. **Run SQL Query**  
   A query groups data by product and calculates total quantity and revenue.

4. **Display and Visualize Results**  
   Results are printed and plotted as a bar chart using `matplotlib`.

## How to Run
1. Open the `sales_summary_task7.ipynb` file in Jupyter Notebook or JupyterLab.
2. Run each cell step by step.
3. The SQLite database and chart image will be created in the same directory.

## Output Example

```
Sales Summary:
  product  total_qty  revenue
0  Apples         15      7.5
1 Bananas         30      9.0
2 Oranges         20      8.0
```

And a bar chart visualizing revenue per product will be displayed.

---
