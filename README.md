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

   - Handled missing values (e.g., `MINIMUM_PAYMENTS`, `CREDIT_LIMIT`)
   - Normalized features using StandardScaler

2. **Exploratory Data Analysis (EDA)**:

   - Statistical summaries
   - Correlation heatmaps to explore feature relationships

3. **Clustering**:

   - K-Means clustering applied
   - Optimal number of clusters determined using Elbow Method and Silhouette Score

4. **Dimensionality Reduction**:

   - PCA reduced features to 2D space for visualization
   - PC1: Spending Behavior
   - PC2: Credit Utilization & Cash Advances

5. **Visualization**:
   - Scatter plot showing clusters and centroids in PCA space
   - Each cluster interpreted based on position and density

---

## 📊 Results & Insights

The PCA visualization identified **6 distinct clusters**, each representing a unique customer segment:

### 🟡 Yellow Cluster — Moderate Spending, High Credit Usage

- Positioned high on PC2, low on PC1
- These users take frequent cash advances and utilize their credit extensively, despite modest spending
- **Suggestions**:
  - Monitor for financial risk
  - Offer budgeting tools, low-interest consolidation options

---

### 🟣 **Indigo** Cluster — Low Spending, Low Credit Use

- Low on both PC1 and PC2
- Very cautious with both spending and borrowing
- **Suggestions**:
  - Encourage engagement with rewards or loyalty programs
  - Promote basic savings products

---

### 🔵 Blue Cluster — High Spending, Mixed Credit Use

- Highest on PC1 (Spending Behavior), moderate on PC2
- Big spenders with diverse card usage patterns
- **Suggestions**:
  - Target with luxury cards, concierge services
  - Retention is key—offer exclusive benefits

---

### 🟢 Green Cluster — Moderate-High Spending, Low Credit Use

- Mid-to-high on PC1, low on PC2
- Spend responsibly without relying on credit or cash advances
- **Suggestions**:
  - Great candidates for credit limit increases
  - Market travel, lifestyle, or cashback cards

---

### 🟦 Teal Cluster — Average Spending, Average Credit Use

- Centered cluster on both axes
- Balanced users with moderate behavior
- **Suggestions**:
  - Offer personalized reward plans
  - Promote flexible card features based on usage

---

### 🟣 **Purple** Cluster — Low Spending, Slight Credit Dependence

- Low on PC1 but moderate on PC2
- Don’t spend much but occasionally rely on credit advances
- **Suggestions**:
  - Educate on credit health and interest charges
  - Introduce credit counseling or micro-loans

---

## 🧠 Strategic Takeaways

- Create tailored marketing strategies per cluster
- Reduce risk by monitoring high credit users
- Focus on premium services for high spenders (Blue, Green)
- Support cautious users with growth options (Purple, Indigo)

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**

### Libraries Used:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/AnandSreekumar03/CreditCard.git
   cd CreditCard
   ```
