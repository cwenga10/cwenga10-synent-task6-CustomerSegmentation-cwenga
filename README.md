# Customer Segmentation using K-Means Clustering

## Project Overview

This project applies **K-Means Clustering** to the Mall Customer Dataset to segment customers based on their demographic and spending behavior. The objective is to identify distinct customer groups that can help businesses develop targeted marketing strategies and improve customer engagement.

---

## Dataset

**Dataset:** Mall Customer Dataset

**Features:**

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1-100)

**Total Records:** 200 customers

---

## Objective

* Preprocess and clean customer data.
* Perform exploratory data analysis (EDA).
* Apply K-Means clustering to identify customer segments.
* Visualize customer groups and generate business insights.

---

# Project Workflow

## 1. Data Loading and Inspection

* Imported the dataset using Pandas.
* Examined data structure and data types.
* Identified features suitable for clustering.

## 2. Data Cleaning

* Checked for missing values and duplicates.
* Verified data consistency.
* Selected relevant features for clustering.

## 3. Exploratory Data Analysis (EDA)

Performed analysis on:

* Income distribution
* Spending score distribution
* Relationship between income and spending score
* Customer behavior patterns

## 4. Model Building (K-Means Clustering)

* Scaled numerical features.
* Applied the Elbow Method to determine the optimal number of clusters.
* Selected **5 clusters**.
* Assigned cluster labels to customers.

## 5. Data Visualization

Created visualizations including:

* Elbow Method plot
  
  ![Elbow Method](screenshots/elbow_method.png)

  
* Customer Segmentation scatter plot

  ![Customer_Segments](screenshots/customer_segments.png)
  
* Correlation Heatmap
  
  ![Correlation_Heat](screenshots/correlation_heatmap.png)

---

# Key Findings

* Total records analyzed: **200**
* Identified **5 distinct customer segments**.
* Clear separation between high-spending and low-spending groups.
* Spending behavior is not strongly dependent on income alone.
* Customer segmentation provides actionable marketing insights.

---

# Customer Segments

### Cluster 0 – Average Customers

* Moderate income and moderate spending.
* Stable customer group with regular purchasing behavior.

### Cluster 1 – High-Value Customers

* High income and high spending score.
* Premium customers with strong revenue potential.

### Cluster 2 – Young High Spenders

* Low income but high spending behavior.
* Potential long-term customers who respond well to marketing campaigns.

### Cluster 3 – Conservative High-Income Customers

* High income but low spending.
* Opportunity for targeted promotions and loyalty incentives.

### Cluster 4 – Low Engagement Customers

* Low income and low spending.
* Require re-engagement strategies and personalized offers.

---

# Business Insights

* High-value customers should receive premium offers and loyalty rewards.
* Moderate-income high spenders represent a strong growth opportunity.
* Low-spending customers can be targeted with personalized promotions.
* Customer segmentation enables more effective and data-driven marketing strategies.

---

# Business Recommendations

1. Focus marketing campaigns on high-value customer segments.
2. Create loyalty programs for moderate-income high spenders.
3. Re-engage low-spending customers through targeted promotions.
4. Use customer segmentation to personalize marketing efforts.

---

# Visualizations

## Elbow Method

Determines the optimal number of clusters for K-Means.

## Customer Segments

Visualizes customer groups based on annual income and spending score.

## Correlation Heatmap

Displays relationships between numerical features.

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

# Future Improvements

* Compare results with Hierarchical Clustering.
* Develop Customer Lifetime Value (CLV) prediction models.
* Build a recommendation system for personalized offers.
* Create an interactive dashboard using Streamlit or Power BI.
* Develop a real-time customer segmentation system.

---

# Conclusion

This project successfully segmented customers into five meaningful groups using K-Means Clustering. The insights generated can help businesses improve customer targeting, optimize marketing campaigns, and increase customer engagement.

---

# Author

**Cwenga Ndzendze**

Data Science Intern – Synent Technologies

Skills: Python | Machine Learning | Data Analytics | Data Visualization | SQL



