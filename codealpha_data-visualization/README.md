Supermarket Sales Visualization

A comprehensive data visualization project analyzing supermarket sales data using Python, with interactive and static visualizations.

Overview

This project performs an exploratory data analysis (EDA) on supermarket sales data, creating various visualizations to understand sales patterns, customer behavior, and product performance across different dimensions.


Dataset

The dataset (supermarket.csv) contains 9,800 transaction records with the following key features:



Order Information: Order ID, Order Date, Ship Date, Ship Mode



Customer Information: Customer ID, Customer Name, Segment (Consumer, Corporate, Home Office)



Geographic Information: Country, City, State, Postal Code, Region



Product Information: Product ID, Category, Sub-Category, Product Name



Sales Information: Sales amount



Requirements

bash

pip install numpy pandas matplotlib seaborn plotly

Visualizations Included

1\. Shipping Days by Ship Mode

Analyzes delivery time distribution across different shipping methods



Shows that shipping times are consistent across ship modes



2\. Product Category Distribution

Pie chart showing sales distribution across categories



Technology (36.52%)



Furniture (32.80%)



Office Supplies (30.68%)



3\. Category Sales by Customer Segment

Count of transactions by category and customer segment



Consumer segment has the highest transaction volume



Office Supplies has the most transactions overall



4\. Average Sales by Category and Segment

Technology has the highest average sale value



Corporate segment shows strong performance in Technology



Consumer segment has lower average values but higher volume



5\. Top Sub-Categories by Transaction Count

Horizontal bar chart of top 10 sub-categories



Binders, Paper, and Furnishings lead in transaction frequency



Key Insights

Technology products generate the highest average sales value (456.4 per transaction)



Consumer segment accounts for the most transactions (over 5,000)



Office Supplies is the most frequently purchased category



Shipping times are consistent across all ship modes (average 3-5 days)



Binders, Paper, and Furnishings are the top sub-categories by transaction volume



 How to Run

Clone this repository



Install dependencies: pip install -r requirements.txt



Place the dataset as supermarket.csv in the project directory



Run the Jupyter notebook: jupyter notebook supermarket-visualization.ipynb



 Notes

The dataset includes missing postal codes that have been handled by filling with Vermont's default ZIP code (05401)



Duplicate records have been removed



Date columns have been properly formatted to datetime objects



 License

This project is for educational and analytical purposes.



 Author - Riya Choudhary

Data analysis and visualization performed using Python's data science stack including Pandas, Matplotlib, Seaborn, and Plotly.

