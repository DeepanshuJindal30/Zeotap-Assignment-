# Project Title: eCommerce Transactions Analysis

## Overview
This project involves analyzing an eCommerce transactions dataset to derive insights, build predictive models, and segment customers. The tasks include:

1. **Exploratory Data Analysis (EDA)**: Understanding the structure of the dataset and extracting key insights.
2. **Lookalike Model**: Recommending similar customers based on profile and transaction history.
3. **Customer Segmentation**: Grouping customers into segments using clustering techniques.

## Datasets Used
The project uses three datasets:

1. **Customers.csv**:
   - Contains details about customers such as `CustomerID`, `CustomerName`, `Region`, and `SignupDate`.
2. **Products.csv**:
   - Includes product information like `ProductID`, `ProductName`, `Category`, and `Price`.
3. **Transactions.csv**:
   - Provides transaction details, including `TransactionID`, `CustomerID`, `ProductID`, `TransactionDate`, `Quantity`, `TotalValue`, and `Price`.

## Task Details

### Task 1: Exploratory Data Analysis (EDA)
- Perform exploratory analysis on the datasets to understand their structure and content.
- Extract insights such as top regions by customer count and top product categories by sales.
- **Output**: Insights are printed to the console.

### Task 2: Lookalike Model
- **Objective**: Recommend the top 3 similar customers for each customer based on their transaction and profile data.
- **Steps**:
  1. Aggregate customer transaction data.
  2. Normalize features and compute cosine similarity.
  3. Identify the top 3 similar customers for each customer.
- **Output**: A CSV file (`Lookalike.csv`) containing similar customer recommendations.

### Task 3: Customer Segmentation
- **Objective**: Segment customers into clusters based on purchasing behavior and demographics.
- **Steps**:
  1. Aggregate customer data and encode categorical features.
  2. Apply clustering algorithms (e.g., K-Means).
  3. Evaluate clusters using Davies-Bouldin Index.
  4. Visualize clusters using PCA.
- **Output**: Cluster visualizations and Davies-Bouldin Index value.

## Installation and Usage

### Prerequisites
- Python 3.x
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn

### Running the Project
1. Place the `Customers.csv`, `Products.csv`, and `Transactions.csv` in the project directory.
2. Run the Python script `ecommerce_analysis.py`.

### Outputs
- **EDA**: Insights displayed in the console.
- **Lookalike Model**: `Lookalike.csv` file containing customer recommendations.
- **Customer Segmentation**: Visualizations displayed and Davies-Bouldin Index printed in the console.

## File Structure
- `ecommerce_analysis.py`: Contains the implementation of all three tasks.
- `Lookalike.csv`: Output of the lookalike model (generated upon execution).
- `Customers.csv`, `Products.csv`, `Transactions.csv`: Input datasets.

## Evaluation
- **EDA**: Quality and relevance of insights derived.
- **Lookalike Model**: Accuracy and logic of recommendations.
- **Clustering**: Metrics (e.g., Davies-Bouldin Index) and visualization quality.

## Author
[Your Name]


