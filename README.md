# Machine Learning Project - Clustering and Classification

This project aims to analyze online retail transaction data from the **Online Retail II** dataset. It consists of two main parts:

1. **Clustering (Customer Segmentation)** using the KMeans algorithm.
2. **Classification (Customer Classification)** by building and comparing three models: Random Forest, Logistic Regression, and Support Vector Machine (SVM).

Through this approach, the project helps to understand customer behavior and predict customer types based on their transaction patterns.

## Dataset

- **Dataset Source:** [Kaggle - Online Retail II](https://www.kaggle.com/datasets/denizcanoguz/online-retail-ii)
- **Dataset Origin:** The dataset records online sales data from a UK-based retail company.
- **File Format:** CSV

### Column Descriptions:

- `Invoice`: Invoice number for each transaction
- `StockCode`: Unique code for each product
- `Description`: Product name
- `Quantity`: Number of product units purchased
- `InvoiceDate`: Date and time of the transaction
- `Price`: Price per unit of the product
- `Customer ID`: Unique ID for each customer
- `Country`: Country of the customer

## Clustering - Customer Segmentation with KMeans

### Objective:
To group customers into different segments based on their shopping behavior, allowing for more targeted marketing strategies.

### Process:
- **Data Preprocessing:** Cleaning data, removing invalid transactions, handling missing values.
- **Features Used:** RFM Analysis (Recency, Frequency, Monetary).
- **Model:** KMeans Clustering.
- **Evaluation:** Using the Silhouette Score to determine the optimal number of clusters.

## Classification - Building a Classification Model

### Objective:
To predict customer segments based on specific features.

### Compared Models:
1. **Random Forest Classifier**
2. **Logistic Regression**
3. **Support Vector Machine (SVM)**

### Steps:
- **Data Splitting:** Train-Test Split
- **Build the Model** 
- **Model Evaluation:** Using metrics such as accuracy, precision, recall, and F1-score.
