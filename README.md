# Customer Segmentation Using K-Means Clustering

## Overview
This project implements customer segmentation using the **K-Means Clustering** algorithm. The aim is to analyze customer data and group them into distinct clusters based on their age, annual income, and spending score. These clusters help in identifying target customer groups for better marketing strategy formulation.

## How It Works
1. **Data Preprocessing**: The dataset is cleaned and preprocessed by encoding categorical variables and scaling the features for optimal clustering results.
2. **Exploratory Data Analysis (EDA)**: Visualizations such as scatter plots, histograms, and pair plots are used to explore the relationships between features and identify patterns in customer data.
3. **K-Means Clustering**: The K-Means algorithm is applied to cluster customers based on their demographics and purchasing behavior.
4. **Cluster Analysis**: Each cluster is analyzed based on characteristics such as average age, income, and spending score, helping to understand the type of customers in each cluster and the potential marketing strategy for each group.

## Techniques Used
- **Data Preprocessing**:
  - Handled missing values and scaled features using `StandardScaler`.
  - Encoded categorical variables (e.g., gender) using `LabelEncoder`.
  
- **Exploratory Data Analysis (EDA)**:
  - Visualized customer distributions using scatter plots, histograms, and pair plots.
  - Analyzed feature relationships to inform clustering decisions.

- **K-Means Clustering**:
  - Implemented the K-Means clustering algorithm using the `sklearn` library.
  - Used the **Elbow Method** to determine the optimal number of clusters.

- **Cluster Visualization**:
  - Visualized clusters using 2D scatter plots to show how customers are grouped based on income and spending score.

- **Cluster Interpretation**:
  - Conducted analysis on each cluster to provide actionable insights, such as identifying high-spending and low-spending customers.

## Requirements
- Python 3.x
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

To install the necessary libraries, run:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
