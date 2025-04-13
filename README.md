# Customer-Segmentation-Recommendation-System

This project analyzes UK-based e-commerce data to segment customers and recommend products using unsupervised learning and behavioral analytics.

## 📊 Dataset
- Source: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Records: 541,909 transactions (2010-2011)
- Fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## 🎯 Objectives
1. Clean and transform raw transactional data
2. Engineer features (RFM, behavioral, geographic, cancellation, seasonal)
3. Cluster customers using K-Means (after PCA)
4. Recommend top-selling products to customers within the same segment

## 🧪 Techniques Used
- Data Cleaning: Handling missing values, cancelled orders, duplicates
- Feature Engineering: RFM, frequency, seasonality, geographic patterns
- Clustering: KMeans with PCA
- Evaluation: Elbow Method, Silhouette Score, 3D Visualization
- Recommendation: Top-N products not purchased by cluster peers

## 🔍 Key Features
- 📦 Isolation Forest for outlier detection
- 📉 PCA to reduce dimensionality and handle multicollinearity
- 📈 KMeans Clustering with Elbow and Silhouette validation
- 📋 Cluster profiling with Radar and Histogram charts
- 🤖 Basic recommender system based on cluster-specific popularity

## 📁 Project Structure
```bash
├── Customer_Segmentation_&_Recommendation_System.ipynb
├── data/
│   └── data.csv (from Kaggle)
├── README.md
