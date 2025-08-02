# 🛍️ Customer Segmentation using KMeans Clustering

This project performs customer segmentation using the **KMeans Clustering** algorithm on the Mall Customers dataset. The aim is to group customers based on their **Annual Income** and **Spending Score** to uncover patterns for targeted marketing strategies.

---

## 📁 Project Structure

├── task2/
│ ├── Mall_Customers.csv # Input dataset (must be placed here)
│ └── customer_segmentation.py # Main Python script
├── Customer_Segments.xlsx # Output file with assigned clusters
└── README.md # This file
---

## 📊 Dataset Overview

**File:** `Mall_Customers.csv`

The dataset contains the following columns:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🧠 Machine Learning Technique

- **KMeans Clustering** is used to segment customers.
- The **Elbow Method** is applied to determine the optimal number of clusters.
- Final segmentation is performed using **5 clusters**.

---

## 🧪 Features Used for Clustering

- `Annual Income (k$)`
- `Spending Score (1-100)`

These two features represent customer spending behavior and are used to form distinct groups.

---

## 📈 Visualizations

- **Elbow Curve**: To help identify the optimal number of clusters (`k`).
- **Scatter Plot**: Visual representation of customer segments, colored by cluster.

---

## 📝 How to Run the Project

### 1. Prerequisites

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
2. Place the Dataset
Ensure the file Mall_Customers.csv is in the task2/ directory.

3. Run the Script
Run the Python script to execute clustering and generate output:


python task2/customer_segmentation.py
📤 Output
A file named Customer_Segments.xlsx is created in the working directory.

It contains the original customer data with an additional Cluster column showing the segment each customer belongs to.

Columns in Output File:

CustomerID

Gender

Age

AnnualIncome

SpendingScore

Cluster

📚 References
Dataset: Kaggle - Mall Customer Segmentation Data

Scikit-learn KMeans: https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html

📬 Contact
For any questions or suggestions, feel free to reach out through GitHub Issues.

🏷️ Tags
Customer Segmentation KMeans Clustering Machine Learning Data Analysis Marketing



---

Let me know if you also want a version formatted for a Jupyter Notebook or if you want a license or co
