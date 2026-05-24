# Iris-Data-Analysis-and-Clustering
An end-to-end data analysis project on the Iris dataset, including data cleaning, exploratory data analysis (EDA), and clustering using K-Means to uncover hidden patterns.
# 🌸 Iris Data Analysis and Clustering

## Overview
This project performs a complete data analysis pipeline on the Iris dataset, including data cleaning, exploratory data analysis (EDA), and unsupervised learning using K-Means clustering.

## Objectives
- Clean and prepare the dataset for analysis
- Explore feature relationships using EDA techniques
- Apply clustering to group similar data points
- Compare clustering results with actual species labels



## Data Cleaning
- Checked for missing values
- Verified data types
- Ensured dataset consistency



## Exploratory Data Analysis (EDA)
- Descriptive statistics (mean, median, standard deviation)
- Correlation analysis
- Data visualization:
  - Heatmap
  - Boxplots
  - Scatter plots
  - Histograms

###  Key Insights
- Petal features show stronger separation between species
- Sepal features have more overlap
- Petal length and width are highly correlated



## Clustering 

### Method Used:
- **K-Means Clustering**

### Steps:
1. Feature scaling using StandardScaler
2. Finding optimal number of clusters (Elbow Method)
3. Applying K-Means algorithm
4. Visualizing clusters

### Results:
- Optimal number of clusters: **K = 3**
- Setosa is clearly separated
- Versicolor and Virginica show slight overlap

###  Evaluation:
- Compared clusters with actual species using cross-tabulation


### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
