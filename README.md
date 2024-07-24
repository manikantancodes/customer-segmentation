# E-commerce Customer Segmentation

## Overview
This project focuses on clustering e-commerce customers based on their activity using the k-means clustering algorithm. Customer segmentation is essential for understanding customer behavior and improving targeting strategies.

## Data Details
The dataset includes customer IDs, gender, order counts, and search frequencies for various brands.

### Variable Description:
- **Cust_ID**: Unique identifier for customers
- **Gender**: Gender of the customer
- **Orders**: Number of orders placed by each customer in the past
- Remaining 35 features represent the number of times customers have searched specific brands

## Project Workflow
1. **Data Preprocessing & Exploratory Data Analysis (EDA)**
   - Handle missing values
   - Analyze the distribution of variables
   - Visualize correlations between features

2. **Model Building with K-means Clustering**
   - Standardize the data
   - Apply Principal Component Analysis (PCA) for dimensionality reduction
   - Determine the optimal number of clusters using the silhouette score
   - Apply k-means clustering to segment customers

3. **Evaluation & Visualization**
   - Analyze cluster characteristics
   - Visualize cluster distributions

## Data Preprocessing
- Missing values are handled by imputing or dropping missing data
- Standardization of features is done to ensure equal importance of all features

## Model Building
- **Principal Component Analysis (PCA)**: Reduces dimensionality to make clustering more efficient and interpretable
- **K-means Clustering**: Segments customers into clusters based on their search and purchase behavior
- **Silhouette Score**: Helps determine the optimal number of clusters

## Scripts
- `customer_segmentation.ipynb`: Contains code for preprocessing, EDA, model training, and evaluation.

## Evaluation Metric
- **Silhouette Score**: Measures how similar an object is to its own cluster compared to other clusters

## Running the Project
To run the customer segmentation project, execute the following command in your terminal:
```bash
python_customer_segmentation.ipynb
