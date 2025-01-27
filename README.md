# Zeotap_Assignment

# Data Science Assignment

## Overview
This project involves performing data analysis and machine learning tasks on an eCommerce transactions dataset. The tasks include Exploratory Data Analysis (EDA), building a Lookalike Model, performing Customer Segmentation, and an optional Predictive Modeling task.

---

## Dataset Description
The dataset contains the following three CSV files:

1. **Customers.csv**
   - **CustomerID**: Unique identifier for each customer.
   - **CustomerName**: Name of the customer.
   - **Region**: Continent where the customer resides.
   - **SignupDate**: Date when the customer signed up.

2. **Products.csv**
   - **ProductID**: Unique identifier for each product.
   - **ProductName**: Name of the product.
   - **Category**: Product category.
   - **Price**: Product price in USD.

3. **Transactions.csv**
   - **TransactionID**: Unique identifier for each transaction.
   - **CustomerID**: ID of the customer who made the transaction.
   - **ProductID**: ID of the product sold.
   - **TransactionDate**: Date of the transaction.
   - **Quantity**: Quantity of the product purchased.
   - **TotalValue**: Total value of the transaction.

---

## Tasks

### 1. Exploratory Data Analysis (EDA)
- Identified missing values, summary statistics, and performed visualizations.
- Key insights include transaction trends, product popularity, and customer distribution by region.

### 2. Lookalike Model
- Built a similarity-based recommendation system using cosine similarity.
- Recommended the top 3 similar customers for the first 20 customers.
- Output stored in `Lookalike.csv`.

### 3. Customer Segmentation
- Performed clustering using K-Means and evaluated clusters using the Davies-Bouldin Index.
- Visualized clusters using PCA.
- Cluster assignments stored in `Clustering.csv`.

---

## File Structure
- **Zeotap_Assignment.py**: Python script containing the code for all tasks.
- **FirstName_LastName_Lookalike.csv**: Lookalike model results.
- **FirstName_LastName_Clustering.csv**: Customer segmentation results.
- **README.md**: This file.

---

## How to Run
1. Install required Python libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

2. Place `Customers.csv`, `Products.csv`, and `Transactions.csv` in the same directory as the script.

3. Run the script:
   ```bash
   python Zeotap_Assignment.py
   ```

4. Outputs:
   - Visualizations will display during execution.
   - Results for Lookalike and Clustering tasks will be saved as CSV files.

---

## Requirements
- Python 3.7+
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

---

## Insights and Results
- **EDA**: Visualized key trends and identified valuable patterns.
- **Lookalike Model**: Generated personalized recommendations for similar customers.
- **Clustering**: Grouped customers into distinct segments with low Davies-Bouldin Index.

---
