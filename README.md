# Hierarchical-Clustering-for-Market-Basket-Analysis




Hierarchical Clustering - Customer Segmentation
This project demonstrates the use of Hierarchical Clustering to segment mall customers based on their annual income and spending score.

Project Structure
HIERARACHICAL.ipynb - Jupyter notebook containing the complete implementation

Mall_Customers.csv - Dataset containing customer information

README.md - This documentation file

Dataset Description
The dataset Mall_Customers.csv contains the following columns:

CustomerID - Unique identifier for each customer

Genre - Gender of the customer (Male/Female)

Age - Age of the customer

Annual Income (k$) - Annual income in thousands of dollars

Spending Score (1-100) - Spending score assigned by the mall (1-100)

Methodology
1. Data Preprocessing
Imported necessary libraries: NumPy, Matplotlib, Pandas

Loaded the dataset and extracted relevant features (Annual Income and Spending Score)

2. Dendrogram Analysis
Used SciPy's hierarchical clustering to create a dendrogram

The dendrogram helps determine the optimal number of clusters by showing the hierarchical relationship between data points

3. Hierarchical Clustering Model
Implemented Agglomerative Clustering with:

5 clusters (determined from dendrogram)

Euclidean distance metric

Ward linkage method

4. Visualization
Created scatter plots to visualize the customer segments

Each cluster is represented with different colors

The plot shows how customers are grouped based on their income and spending patterns

Key Findings
The hierarchical clustering algorithm successfully segments customers into 5 distinct groups based on their spending behavior and income levels. These segments can help the mall:

Target marketing campaigns more effectively

Understand customer behavior patterns

Optimize product placement and promotions

Requirements
To run this project, you need:

Python 3.x

Jupyter Notebook

Pandas

NumPy

Matplotlib

Scikit-learn

SciPy

Usage
Clone the repository

Open HIERARACHICAL.ipynb in Jupyter Notebook

Run all cells to see the complete analysis

The dataset Mall_Customers.csv should be in the same directory

Results
The final visualization shows 5 customer clusters with clear separation, indicating distinct customer segments that can be targeted with different marketing strategies.
