**Objective**
Analyze sales data using Python and visualize insights such as monthly trends and region-wise performance.

**Files Included**
File Name	Description
sample_sales_data_full.csv	CSV file containing sales data with date, product, region, sales, units sold, and unit price
sales_analysis.ipynb	Jupyter Notebook with code to load, analyze, and visualize the data
README.md	This readme file with project description

**Technologies Used**
Python 3
Pandas (data handling)
Matplotlib (visualizations)
Jupyter Notebook 

**Key Analysis Performed**
Loaded sales data from CSV using pandas.read_csv()
Converted date column to datetime using pd.to_datetime()
Grouped data by month using .dt.to_period('M')
Created line chart showing monthly sales trend
plotted Bar Chart of total sales by product
Plotted pie chart of region-wise sales

**Charts**
Monthly Sales Trend (Line Chart)
Region-wise Sales Comparison (Pie Chart)
Total sales by product(Bar Chart)

