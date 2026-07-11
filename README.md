# Sales Data Analysis Project

## Project Title

Complete Sales Data Analysis using Python

## Project Overview

This project performs a complete data analysis pipeline on a sales dataset. The analysis includes loading the dataset, cleaning missing or duplicate values, analyzing sales performance, creating visualizations, and writing meaningful business insights.

The dataset used in this project is named **sales_data.csv**.

## Dataset Columns

The dataset contains the following columns:

| Column Name | Description                   |
| ----------- | ----------------------------- |
| Date        | Date of the sales transaction |
| Product     | Name of the product sold      |
| Quantity    | Number of units sold          |
| Price       | Price of one unit             |
| Customer_ID | Unique customer ID            |
| Region      | Sales region                  |
| Total_Sales | Total sales amount            |

## Technical Requirements Covered

This project covers the following requirements:

* Complete data analysis pipeline
* Data loading using pandas
* Data cleaning and preprocessing
* Data validation
* Basic sales analysis
* At least 2 different chart types
* Visualizations using matplotlib
* Meaningful written insights
* Professional formatting and documentation

## Tools and Libraries Used

* Python
* pandas
* matplotlib
* Jupyter Notebook

## Project Workflow

## Day 1-2: Project Setup

* Chose the topic: Sales Data Analysis
* Collected the dataset
* Created the project structure
* Imported required Python libraries

## Day 3: Data Exploration

* Loaded the dataset using pandas
* Displayed the first few rows
* Checked dataset shape
* Checked column names
* Checked missing values
* Checked duplicate records
* Viewed statistical summary

## Day 4: Basic Analysis

The following metrics were calculated:

* Total revenue
* Total quantity sold
* Average sales value
* Average product price
* Total unique customers
* Product-wise sales
* Region-wise sales
* Product-wise quantity sold
* Monthly sales trend

## Day 5: Data Visualization

The following charts were created using matplotlib:

1. Product-wise Total Sales Bar Chart
2. Region-wise Sales Pie Chart
3. Monthly Sales Trend Line Chart
4. Quantity vs Total Sales Scatter Plot

## Day 6: Report and Insights

Meaningful insights were written based on the analysis and visualizations.

## Day 7: Finalization

* Checked the code
* Fixed possible errors
* Verified the output
* Prepared the project for submission

## Data Cleaning Steps

The following cleaning steps were applied:

* Removed duplicate rows
* Converted the Date column into datetime format
* Converted numeric columns into proper numeric data types
* Filled missing numeric values using median
* Filled missing categorical values using "Unknown"
* Removed invalid date records
* Recalculated Total_Sales using Quantity × Price

## Visualizations

### 1. Product-wise Total Sales Bar Chart

This chart shows which product generated the highest revenue.

### 2. Region-wise Sales Pie Chart

This chart shows the sales contribution of each region.

### 3. Monthly Sales Trend Line Chart

This chart shows how sales changed over time.

### 4. Quantity vs Total Sales Scatter Plot

This chart shows the relationship between quantity sold and total sales.

## Meaningful Insights

1. The highest revenue-generating product can be identified using product-wise sales analysis.

2. The best performing region can be found using region-wise sales analysis.

3. The most sold product by quantity helps understand customer demand.

4. Monthly sales trend helps understand business growth or decline over time.

5. The scatter plot shows that higher quantity generally leads to higher total sales.

6. Product-wise analysis helps businesses focus on high-performing products.

7. Region-wise analysis helps identify strong and weak market areas.

## Conclusion

This project successfully completes a full data analysis pipeline. The sales dataset was loaded, validated, cleaned, analyzed, and visualized using Python. The results from this analysis can help businesses make better decisions related to product planning, sales strategy, and regional marketing.

## How to Run the Project

1. Open Jupyter Notebook.

2. Place the dataset file in the same folder as the notebook.

3. Make sure the dataset name is:

```text
sales_data.csv
```

4. Install the required libraries:

```bash
pip install pandas matplotlib
```

5. Run each notebook cell step by step.

## Expected Output

After running the notebook, the following outputs will be generated:

* Cleaned dataset
* Sales summary metrics
* Product-wise sales analysis
* Region-wise sales analysis
* Monthly sales trend
* Bar chart
* Pie chart
* Line chart
* Scatter plot
* Written insights
* Final conclusion

## Author

Aravinthan G

## Project Type

Data Analysis Project

## Dataset Name

sales_data.csv
