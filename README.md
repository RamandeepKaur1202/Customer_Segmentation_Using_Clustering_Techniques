# Customer Segmentation using Clustering Techniques

## Project Overview

This project focuses on **customer segmentation** using **unsupervised machine learning techniques**. The goal is to group customers based on their **annual income** and **spending behavior** so that businesses can make **data-driven marketing and customer engagement decisions**.

Customer segmentation helps organizations understand different types of customers and design **personalized strategies** for retention, promotions, and loyalty programs.



## Objectives

- Segment customers based on purchasing behavior
- Identify meaningful customer groups using clustering algorithms
- Evaluate and compare clustering performance
- Derive actionable business insights from clusters



## Dataset

- **Dataset Name:** Mall Customers Dataset
- **Features Used:**
  - Annual Income (k\$)
  - Spending Score (1–100)

These features are commonly used to understand customer purchasing capacity and behavior.



## Technologies & Tools

- **Programming Language:** Python
- **Libraries Used:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - SciPy



## Methodology

1. **Data Loading & Exploration**\
   The dataset was loaded and explored to understand its structure and key statistics.

2. **Feature Selection**\
   Annual income and spending score were selected as the primary features for clustering.

3. **Feature Scaling**\
   StandardScaler was applied since clustering algorithms are distance-based.

4. **K-Means Clustering**

   - Elbow Method was used to determine the optimal number of clusters (K = 5)
   - Model performance was evaluated using the **Silhouette Score**

5. **Hierarchical Clustering**

   - Agglomerative clustering was applied for validation
   - Dendrograms were used to visualize cluster formation



## Model Evaluation

- **K-Means Silhouette Score:** \~0.555
- **Hierarchical Clustering Silhouette Score:** \~0.554

Both models showed comparable performance, with K-Means being slightly more efficient and easier to interpret for this dataset.



## Results & Insights

The clustering process identified **five distinct customer segments**, such as:

- High income, high spending customers (premium customers)
- Low income, low spending customers (budget-conscious customers)
- High income, low spending customers (careful spenders)

These insights can help businesses:

- Design targeted marketing campaigns
- Improve customer retention
- Personalize offers and recommendations



## Conclusion

K-Means clustering proved to be the most suitable model for this dataset due to its efficiency and clear cluster separation. Hierarchical clustering complemented the analysis by providing better interpretability through dendrogram visualization. Overall, the project demonstrates how clustering techniques can convert raw customer data into **actionable business insights**.



## Future Scope

- Apply **PCA** for dimensionality reduction and better visualization
- Experiment with **Gaussian Mixture Models (GMM)**
- Include additional features such as age, gender, and purchase frequency



## Author

**Ramandeep Kaur**\
B.Tech – Computer Science Engineering


