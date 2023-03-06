# KPrototype Segmentation of Open University Students

## Introduction

This project aims to segment students of the Open University using a KPrototype-based clustering algorithm in PySpark on Azure Databricks. The data was read from EDMViews present in the Data Lake Gen2, and exploratory data analysis and statistical analysis were performed to better understand the data and the clusters formed.

## Technical Details

The KPrototype algorithm used in this project is a type of clustering algorithm that combines the properties of K-means and K-modes algorithms to handle both numerical and categorical data. In this project, PySpark was used as the primary tool for data processing and clustering. The project was executed on Azure Databricks, which is a cloud-based platform for big data processing and analytics.

## Data Preparation

Before applying the KPrototype algorithm, the data was preprocessed to handle missing values and outliers. The numerical data was scaled to ensure that the attributes with larger values did not dominate the clustering process. Categorical data was transformed into a numerical representation to be used in the clustering algorithm.

## Exploratory Data Analysis

Exploratory data analysis was performed to better understand the characteristics of the data and the relationships between the variables. The distribution of each attribute was visualized, and the correlation between attributes was calculated. This helped to identify potential outliers and relationships between variables that could impact the clustering results.

## Statistical Analysis

A Hopkins test was performed to check the suitability of the data for clustering. Additionally, Pearson correlation test (for numerical variables) & chi-square test (for categorical variables) was performed to identify the significance of the relationships between the variables and the clusters formed. These tests helped to validate the results of the clustering process and to ensure that the clusters formed were meaningful and representative of the data.

## Clustering Results

The KPrototype algorithm was applied to the preprocessed data, and the results were visualized to understand the characteristics of the clusters formed. The number of clusters was determined based on the results of the Elbow graph and the visualizations of the data. The results of the clustering process can be used to better understand the characteristics of the students in each cluster and to develop targeted strategies for each group.

## Conclusion

This project demonstrates the use of KPrototype-based clustering in PySpark on Azure Databricks to segment students of the Open University. The KPrototype algorithm was able to handle both numerical and categorical data, providing a comprehensive representation of the students. The results of the clustering process can be used to gain a deeper understanding of the characteristics of the students and to develop targeted strategies to better support their learning experience.

## Limitations

Please note that due to privacy reasons, the data used in this project cannot be provided. This limits the ability to replicate the results of this study and to fully understand the methods and techniques used.
