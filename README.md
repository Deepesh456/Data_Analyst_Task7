# Grocery Sales Data Analysis with MySQL and Python

This project presents a sales data analysis of grocery products using a MySQL database and Python. The analysis is conducted inside a Jupyter Notebook and includes querying, summarizing, and visualizing the data.

## Objective

- Connect Python to a MySQL database using SQLAlchemy and PyMySQL
- Use SQL to aggregate sales data (quantity and revenue)
- Visualize key metrics using bar and pie charts

## Tools and Technologies

- Jupyter Notebook
- Python 3
- MySQL
- SQLAlchemy
- PyMySQL
- pandas
- matplotlib

## Dataset Overview

The data is stored in a MySQL table named `sales`, containing records of grocery transactions with:
- Product name
- Quantity sold
- Unit price

The notebook performs SQL-based analysis to extract and visualize this data.

## Key Visualizations

| Chart File                | Description                                      |
|---------------------------|--------------------------------------------------|
| `sales_chart.png`         | Total revenue by product                         |
| `revenue_vs_quantity.png` | Comparison of revenue vs quantity sold           |
| `top5_products.png`       | Top 5 revenue-generating products                |
| `top5_pie_chart.png`      | Revenue share distribution (pie chart)           |

## How to Run

1. Clone the repository  
2. Ensure MySQL server is running and the `sales_data` database is created  
3. Install required packages:

```bash
pip install -r requirements.txt
```

4. Launch the notebook:

```bash
jupyter notebook Sales.ipynb
```

## Output

The notebook generates visualizations and saves them as `.png` files for easy review. These visuals help analyze which products generate the most revenue and how sales are distributed across the catalog.

## Files in This Project

- `Sales.ipynb` – Main analysis notebook  
- `*.png` – Generated charts  
- `README.md` – Project documentation  
- `requirements.txt` – Package dependencies  
