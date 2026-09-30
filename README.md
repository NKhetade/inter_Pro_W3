# Week 3: Customer Segmentation Using K-Means

## Overview

This project focuses on **Unsupervised Learning and Clustering Analysis** using Python and the Mall Customer Segmentation dataset from Kaggle. The K-Means algorithm is used to group customers based on their annual income and spending score.

## Objectives

* Explore customer income and spending-score distributions.
* Apply feature standardization using `StandardScaler`.
* Determine the number of clusters using the Elbow Method and Silhouette Score.
* Perform K-Means clustering with 5 clusters.
* Visualize and interpret customer segments.

## Dataset

* **Source:** [Mall Customer Segmentation – Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
* **File:** `Mall_Customers.csv`
* **Features:** Annual Income (k$) and Spending Score (1–100).

## Tools and Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook / VS Code

## Project Structure

```text
week3-customer-clustering/
├── Mall_Customers.csv
├── Mail_Seg_Week3.ipynb
├── clustered_customers.csv
├── cluster_profiles.csv
├── Charts/
│   ├── Mail_customers_loaded.png
│   ├── Annual_income_distribution.png
│   ├── Spending_score_distribution.png
│   ├── Elbow_method.png
│   ├── Silhouette_score_graph.png
│   ├── KMeans_customer_segmentation.png
│   ├── Customers_by_cluster.png
│   ├── Cluster_profile_heatmap.png
│   └── Age_spending_by_cluster.png
├── Week3_report.docx
└── README.md
```

## Installation and Execution

Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

Run the Python script:

```bash
Mail_Seg_Week3.ipynb
```

**Note:** Create the `visualizations`, `outputs`, and `reports` folders before running or saving files to them. Place `Mall_Customers.csv` in the project root directory.

## Key Results

* Evaluated cluster counts from K = 2 to K = 10.
* Selected **K = 5** for the final segmentation.
* Evaluated the model using inertia and silhouette score.
* Generated visualizations and customer cluster profiles.

## Learning Outcomes

* Understanding unsupervised machine learning.
* Applying K-Means clustering and feature standardization.
* Evaluating clustering performance.
* Interpreting customer segments using visualizations and statistics.

## Conclusion

This project demonstrates how K-Means clustering can identify customer groups based on income and spending behavior. The analysis provides a foundation for customer profiling and exploratory marketing analysis.

