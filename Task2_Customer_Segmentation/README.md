# 🛍️ Customer Segmentation Using K-Means Clustering

## 📌 Internship Task - DevelopersHub Corporation

---

## 🎯 Objective

The goal of this project is to segment customers based on their purchasing behavior using **unsupervised learning (K-Means Clustering)**.  
This helps businesses understand different customer groups and design targeted marketing strategies.

---

## 📊 Dataset

**Mall Customers Dataset**

The dataset contains the following features:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## ⚙️ Tools & Technologies

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- PCA (Principal Component Analysis)

---

## 🧠 Methodology

### 1. Data Preprocessing
- Removed irrelevant column (`CustomerID`)
- Encoded categorical variable (`Gender`)
- Selected important features:
  - Annual Income
  - Spending Score

### 2. Feature Scaling
- StandardScaler used to normalize data before clustering

### 3. Finding Optimal Clusters
- Applied **Elbow Method**
- Determined optimal number of clusters (K = 5)

### 4. K-Means Clustering
- Applied K-Means algorithm to segment customers
- Assigned cluster labels to each customer

### 5. Dimensionality Reduction
- Used **PCA** to visualize clusters in 2D space

---

## 📈 Results

The algorithm successfully divided customers into 5 distinct segments:

- High Income, High Spending → Premium Customers
- High Income, Low Spending → Potential Customers
- Low Income, High Spending → Impulsive Buyers
- Low Income, Low Spending → Budget Customers
- Average Customers → Standard Group

---

## 📊 Visualizations

- Elbow Method Graph (Optimal K selection)
- K-Means Cluster Plot
- PCA Cluster Visualization

---

## 💡 Business Insights

- Premium customers should be targeted with loyalty programs
- Budget customers respond better to discounts and offers
- Potential customers can be converted using personalized marketing
- Impulsive buyers should be controlled using smart recommendations

---

## 🚀 Key Learnings

- Unsupervised Learning (K-Means Clustering)
- Customer segmentation techniques
- Feature scaling importance
- Dimensionality reduction using PCA
- Business strategy development from data
