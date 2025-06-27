# 🧩 Customer Segmentation using KMeans Clustering

This project applies **unsupervised machine learning** (KMeans Clustering) to segment customers based on their demographic and behavioral data. The goal is to help marketing teams target different customer groups more effectively.

---

## 🎯 Objective

To group similar customers together using clustering techniques, enabling:
- Better personalization in marketing campaigns
- Improved customer experience
- Targeted product recommendations

---

## 📊 Dataset Description

The dataset used contains information about customers and their behaviors, including:

- **Demographics**: Age, Income, Marital Status, Number of Children
- **Spending Habits**: Amounts spent on products like wines, fruits, meats, fish, etc.
- **Campaign Interaction**: Responses to past marketing campaigns
- **Enrollment Info**: Year and month the customer joined

> Dataset Source: Included as `marketing_campaign.csv`

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Libraries**:
  - `pandas`, `numpy` — Data manipulation
  - `matplotlib`, `seaborn` — Data visualization
  - `sklearn` — Machine learning (KMeans Clustering)

---

## 🔍 Project Steps

1. **Data Loading**  
   Load the marketing campaign dataset and inspect the structure.

2. **Data Cleaning**  
   Handle missing values, drop irrelevant columns, and format dates.

3. **Feature Selection & Scaling**  
   Select numerical features relevant for clustering and apply scaling.

4. **Elbow Method**  
   Determine the optimal number of clusters using the elbow plot.

5. **KMeans Clustering**  
   Train the clustering model and assign cluster labels to each customer.

6. **Visualization**  
   Visualize cluster distributions to understand key differences.

7. **Interpretation**  
   Analyze the features of each cluster to derive marketing insights.

---

## 📈 Sample Insights

- **Cluster 0**: High-income, luxury buyers
- **Cluster 1**: Younger, low-spending customers
- **Cluster 2**: Moderate-income, loyal spenders with families

---

## 💾 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/shashwat-dev1/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans
