# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies unsupervised machine learning to segment mall customers 
into distinct groups based on their demographic and spending behavior. Built 
as part of my Industrial Training (Project 3) at DecodeLabs.

## 🎯 Objective
Use distance-based clustering algorithms to discover hidden groupings in 
unlabeled customer data, and translate those clusters into actionable 
business personas.

## 📊 Dataset
Mall Customer Segmentation Dataset (200 customers)
- CustomerID
- Genre (Gender)
- Age
- Annual Income (k$)
- Spending Score (1-100)

## 🛠️ Methodology
1. **Preprocessing** — Encoded categorical data, standardized features using StandardScaler
2. **Dimensionality Reduction** — Applied PCA to reduce feature space
3. **Optimal K Selection** — Used Elbow Method and Silhouette Score to 
   mathematically validate the optimal number of clusters
4. **Clustering** — Applied K-Means (K=5) to segment customers
5. **Persona Translation** — Mapped clusters back to interpretable business personas

## 🔍 Key Findings — Customer Personas

| Cluster | Age | Income | Spending | Persona | Recommended Action |
|---|---|---|---|---|---|
| 0 | ~26 | ~$49k | ~73 | Young Enthusiasts | Social media & influencer marketing |
| 1 | ~39 | ~$49k | ~43 | Average Customers | Loyalty programs, seasonal discounts |
| 2 | ~55 | ~$43k | ~24 | Cautious Seniors | Clear value pricing, basic utility |
| 3 | ~30 | ~$80k | ~73 | High-Value Trendsetters | VIP treatment, early access |
| 4 | ~47 | ~$74k | ~30 | Affluent Conservatives | Personalized service, trust-building |

## 🧰 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn (KMeans, PCA, StandardScaler, silhouette_score)
- Matplotlib, Seaborn

## 📈 Results
Successfully identified 5 distinct customer segments with clear separation, 
validated using Silhouette Score analysis, enabling targeted marketing 
strategies for each group.

## 🚀 How to Run
1. Clone this repo
2. Open `[your_notebook_name].ipynb` in Google Colab or Jupyter
3. Run all cells sequentially
