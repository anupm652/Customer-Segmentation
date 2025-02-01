# Customer Segmentation using k-Means Clustering

This project performs **customer segmentation** on the **Mall Customer Segmentation Dataset** using **k-Means clustering**. The goal is to group customers into distinct clusters based on their annual income and spending score.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Steps](#steps)
4. [Results](#results)
5. [Requirements](#requirements)
6. [How to Run](#how-to-run)
7. [License](#license)

---

## Project Overview
Customer segmentation is a common unsupervised learning task that involves grouping customers into clusters based on their behavior or characteristics. In this project, we:
- Preprocess the data (feature selection, standardization).
- Apply **k-Means clustering** to group customers.
- Visualize the clusters and interpret the results.

---

## Dataset
The dataset used in this project is the **Mall Customer Segmentation Dataset**, which contains information about customers' annual income and spending scores.

- **Source:** [Mall Customer Segmentation Dataset on Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **File:** `Mall_Customers.csv`
- **Columns:**
  - `CustomerID`: Unique ID for each customer.
  - `Gender`: Gender of the customer (Male/Female).
  - `Age`: Age of the customer.
  - `Annual Income (k$)`: Annual income in thousands of dollars.
  - `Spending Score (1-100)`: Spending score assigned by the mall (1-100).

---

## Steps
1. **Data Loading and Exploration:**
   - Load the dataset and explore its structure.
   - Check for missing values and feature distribution.

2. **Feature Selection:**
   - Select relevant features (`Annual Income (k$)` and `Spending Score (1-100)`).

3. **Data Preprocessing:**
   - Standardize the data for clustering.

4. **Clustering:**
   - Use the **Elbow Method** to determine the optimal number of clusters.
   - Apply **k-Means clustering** to group customers.

5. **Visualization:**
   - Plot the clusters to visualize customer segments.

6. **Interpretation:**
   - Analyze the clusters and derive actionable insights.

---

## Results
- **Optimal Number of Clusters:** 5
- **Cluster Characteristics:**
  - **Cluster 0:** Low Income, Low Spending
  - **Cluster 1:** High Income, High Spending
  - **Cluster 2:** Middle Income, Middle Spending
  - **Cluster 3:** Low Income, High Spending
  - **Cluster 4:** High Income, Low Spending

---

## Requirements
To run this project, you need the following Python libraries:
- pandas
- scikit-learn
- seaborn
- matplotlib

You can install the required libraries using:
```bash
pip install -r requirements.txt
