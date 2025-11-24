# sales-project-2025
this project is created by alae khellifi ,sabrina hamrouie and maroua makhloufi 
# about this project 
This project analyzes and visualizes **monthly sales data** for four products over one year using:
* **NumPy**
* **Pandas**
* **Matplotlib**
The goal is to **generate**, **process**, and **summarize** sales data, then extract key business insights such as:

* Best-performing product
* Best month
* Best quarter
* Sales distribution and trends

## 📁 **Project Structure**

```
project_sales/
│
├── notebook.ipynb      
├── utils.py            
│
└── data/
    ├── initial.csv     
    ├── final.csv       
    └── output.csv     
```

#how the project works 

#data Generation

* Monthly dates for the full year (2025)
* Random sales for 4 products using `generate_random_sales()` from `utils.py`
* Saved as initial.csv

#build the Final DataFrame

The notebook computes:

* Total sales per month
* Average sales
* Month over month growth
* Quarter assignment
* Highest selling product per month
* Lowest selling product per month

Saved as final.csv

#pivot Tables

* Average quarterly sales per product
* Total sales per quarter

Saved as output.csv

#visualizations Included

* Line chart (monthly trend for each product)
* Stacked bar chart (total monthly sales)
* Heatmap (monthly values per product)
* Boxplot (distribution per product)

performance differences



#key Insights Extracted

The notebook identifies:
* Best month
* Best product(highest total yearly sales)
* Best quarter

These insights support business planning and strategy
