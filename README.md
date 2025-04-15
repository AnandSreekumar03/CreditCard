# 🧠 Credit Card Customer Clustering

This project applies unsupervised learning (clustering) techniques to segment credit card customers based on their usage behavior. The insights from this clustering model can help financial institutions identify different types of users for better targeting, offers, and risk assessment.

---

## 📁 Dataset

- **File**: `CC GENERAL.csv`
- **Source**: [Credit Card Dataset from Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)
- **Description**: An anonymized dataset containing credit card usage information for customer segmentation. Features include:
  - `BALANCE`, `PURCHASES`, `CREDIT_LIMIT`, `PAYMENTS`, `MINIMUM_PAYMENTS`, `TENURE`, and more.

---

## 🔍 Project Overview

### ✅ Objectives

- Clean and preprocess the dataset
- Identify optimal number of customer clusters
- Visualize and interpret each cluster’s behavior

### 🧪 Steps:

1. **Data Cleaning**:

   - Handling missing values
   - Normalizing features

2. **Exploratory Data Analysis (EDA)**:

   - Statistical summary
   - Correlation analysis

3. **Clustering**:

   - K-Means algorithm
   - Elbow Method and Silhouette Score for optimal cluster count

4. **Visualization**:
   - Cluster plots using PCA
   - Box plots to understand feature distributions in clusters

---

## 📊 Results & Insights

Based on the customer segmentation, here are the simplified insights for each cluster:

- **Yellow Cluster (High Credit Use, Moderate Spending)**:

  - These users often borrow more and spend a medium amount.
  - Suggest offering low-interest plans, debt support, or balance transfers.
  - They might be at financial risk and need careful monitoring.

- **Purple Cluster (Low Spending, Low Credit Use)**:

  - These users are very careful with their spending and borrowing.
  - Encourage more card use through cashback or rewards.
  - Good candidates for budgeting tools or saving plans.

- **Green Cluster (Higher Spending, Low Credit Use)**:

  - These customers are financially stable and use credit wisely.
  - Could be offered premium cards or higher credit limits.
  - Great fit for lifestyle rewards and VIP perks.

- **Teal/Turquoise Cluster (Average Spending, Mixed Credit Use)**:

  - Spending habits vary in this group.
  - Personalized offers work best—like dining, travel, or shopping rewards.
  - Can benefit from targeted card features.

- **Blue Cluster (High Spending, Mixed Credit Use)**:
  - Big spenders with diverse usage.
  - Best suited for luxury cards, exclusive services, and high-end rewards.
  - Focus on keeping them happy and loyal.

### Strategic Suggestions:

- Create different marketing plans for each group.
- Offer products and services that match each group’s habits.
- Adjust customer service level based on customer value.
- Help Yellow Cluster manage risk better.
- Focus on keeping Blue and Teal Clusters with premium benefits.

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `sklearn`

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-clustering.git
   cd credit-card-clustering
   ```
