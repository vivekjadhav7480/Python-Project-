# SimpleDataFrame: 

# Description:
This project introduces a lightweight implementation of a DataFrame-like structure, inspired by Pandas. The SimpleDataFrame class provides basic functionality for handling and manipulating tabular data in Python. It’s designed for simplicity and clarity, making it a great learning tool for understanding the core concepts behind DataFrame operations.

# Features:

1. # Data Initialization:
Initialize the DataFrame using a dictionary, where keys represent column names, and values are lists of data. The class automatically calculates the number of rows.


2. Display Data:
View the data in a clean, tabular format with headers.


3. Column Selection:
Select specific columns to create a new DataFrame with just those columns.


4. Row Filtering:
Filter rows based on custom conditions using lambda functions or other callable expressions.


5. Add Columns:
Dynamically add new columns to the DataFrame while maintaining row consistency.


6. Summary Statistics:
Generate basic statistical summaries (minimum, maximum, and average) for numeric columns.



**Usage Examples:**

# Display the full DataFrame.

Select specific columns, e.g., Name and Salary.

Filter rows based on conditions, e.g., Salary > 55000.

Add new columns, e.g., compute a Bonus column as 10% of the Salary.

Summarize numeric data for quick insights.


**Why This Project?** 

# This implementation was created as a hands-on exercise to understand how DataFrame-like structures work internally. Unlike fully-featured libraries like Pandas, this project focuses on implementing core concepts in a simple and approachable way.

# How to Use: 

 1. Clone this repository to your local machine.


2. Import the SimpleDataFrame class into your Python script or notebook.


3. Create a SimpleDataFrame object by passing your data as a dictionary.


4. Use the various methods (display, select_columns, filter_rows, etc.) to manipulate and analyze your data.



# This project is a great starting point for anyone looking to build a deeper understanding of how tabular data structures operate in Python. Contributions and improvements are welcome!

