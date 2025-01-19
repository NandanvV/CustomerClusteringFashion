# Customer Segmentation Using Clustering for Fashion Retail

This project focuses on customer segmentation for a fashion retail dataset using K-means clustering algorithm. 
The goal is to identify distinct customer groups based on purchasing behavior, preferred payment methods, 
and other features and analyze them.

--

## Features
- **Fashion Retail Sales Dataset**: Collection of data representing sales transactions from a clothing store:
  - Customer Reference ID
  - Item Purchased: Name of the item
  - Purchase Amount (USD): Price
  - Date Purchase: Date of Purchase
  - Review Rating: Rating from 1 to 5
  - Payment Method: Credit Card or Cash


 ## Methodology
- **Clustering Algorithm**: K-means
- **Preprocessing Steps**:
  1. Missing values imputed using medians.
  2. Label encoding categorical features.
  3. Aggregating data and implementing feature engineering to end up with meaninful features for each customer.
     - Engineered Features: Most purchased Category, Preferred Payment Method, Average Rating, Buying Frequency,
       Average Purchase Cost
  4. Optimal amount of clusters determined using the elbow method.
  5. Optimal amount of PCA components determined using Explained Variance Ratio.
 
  Programming Language: 3.12.5
  Libraries: Pandas, Scikit learn, Matplotlib, Seaborn

 ---

## Results
- **Cluster Insights**:
  - **Cluster 0**: Low spenders, full body, footwear and accesory buyers who pay with cash.
  - **Cluster 1**: Low spenders, credit card users through all product categories.
  - **Cluster 2**: High spenders using credit card, through all categories with preferences for some categories.

<img width="827" alt="image" src="https://github.com/user-attachments/assets/7f6d4a1d-9633-49ed-8533-261467a3e8f1" />

<img width="465" alt="image" src="https://github.com/user-attachments/assets/dfe5a3e4-f837-4b67-8daf-52f63e00544c" />

<img width="1032" alt="image" src="https://github.com/user-attachments/assets/33aae5c4-e3e9-42be-ac6a-cc2f08196cad" />
