# Sales-Analysis
I have used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data.
The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

I have started by cleaning data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once I have cleaned up data a bit,I moved to the data exploration section. In this section I have explored 3 high level business questions related to my data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product

To answer these questions I have walked through many different pandas & matplotlib methods. They include:
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize results
- Labeling graphs
