# Customer Segmentation using RFM Analysis and K-Means Clustering

This repository contains a Jupyter Notebook that demonstrates the process of customer segmentation using RFM (Recency, Frequency, Monetary Value) analysis and K-Means clustering. The notebook uses PySpark and various data visualization libraries to perform the segmentation and visualize the results.

## Table of Contents

1. **Introduction**
   - Brief overview of customer segmentation using RFM analysis and K-Means clustering.

2. **Setup**
   - Importing required libraries.
   - Initializing Spark and necessary modules.

3. **Data Import**
   - Loading the dataset from an Excel file ("Online Retail.xlsx").
   - Exploring the dataset's basic information.

4. **Data Preprocessing**
   - Removing rows with missing `CustomerID` values.
   - Converting `InvoiceDate` to a date format and calculating `TotalSum`.
   - Creating the RFM (Recency, Frequency, MonetaryValue) table.

5. **Exploratory Data Analysis (EDA)**
   - Visualizing the distribution of `Frequency`, `Recency`, and `MonetaryValue`.
   - Identifying and handling negative `MonetaryValue` values.

6. **Feature Scaling**
   - Using VectorAssembler to prepare features for scaling.
   - Applying StandardScaler for feature scaling.
   - Generating scaled data for further analysis.

7. **RFM Segmentation**
   - Creating RFM segments based on score ranges.
   - Assigning RFM segments to each customer.
   - Visualizing RFM segments' distribution.
   - Analyzing mean RFM values for each segment.

8. **K-Means Segmentation**
   - Removing outliers from the dataset.
   - Determining the optimal number of clusters using Silhouette Score.
   - Training K-Means clustering with the optimal number of clusters.
   - Analyzing and visualizing K-Means clusters.

9. **Results and Insights**
   - Summarizing customer segments and their characteristics.
   - Visualizing the averages of RFM/K-Means segments using bar plots.

10. **Conclusion**
    - Recap of the performed analyses.
    - Key findings and insights from customer segmentation.

## Instructions

1. Make sure you have Python and PySpark installed in your environment.
2. Clone this repository to your local machine.
3. Download the "Online Retail.xlsx" dataset and place it in the same directory as the notebook.
4. Open the Jupyter Notebook in your preferred environment.
5. Run each cell in the notebook sequentially to perform the analysis and generate visualizations.
6. Explore the insights and conclusions drawn from the analysis.

