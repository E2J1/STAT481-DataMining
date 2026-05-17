# 📊 STAT481 – Fundamentals of Data Mining

This project was completed as part of the **STAT481: Fundamentals of Data Mining** course at the University of Bahrain.

## 👥 Team
- **Ebrahim Juma Alsawan**
- **Ali Sameer**

## 🎯 Project Objective

Apply classification, clustering, and association rule mining techniques on real-world financial and retail datasets to uncover insights and evaluate predictive performance.

---

# 🔍 1. Loan Approval Classification

Built machine learning classification models to predict loan approvals using financial and demographic features.

## 🛠 Techniques Used

- Decision Trees
- Random Forest
- Feature Importance Analysis
- Confusion Matrix Evaluation
- Model Performance Metrics

## 📈 Results

- Accuracy: **92.56%**
- AUC Score: **0.97**

## 📌 Key Insights

- Credit score strongly influenced loan approval outcomes.
- Interest rate and income-to-loan ratio were major predictive features.
- Random Forest significantly improved prediction performance.

## 📷 Project Visuals

<p align="center">
  <img src="images/confusion_matrix.png" width="45%">
  <img src="images/feature_importance.png" width="45%">
</p>

<p align="center">
  <img src="images/roc_curve.png" width="60%">
</p>

---

# 📈 2. Hierarchical Clustering & Customer Segmentation

Performed clustering analysis to identify meaningful customer groupings using hierarchical clustering methods.

## 🛠 Techniques Used

- Agglomerative Clustering
- Dendrogram Visualization
- Single Linkage
- Complete Linkage
- Ward Linkage

## 📌 Key Insights

- Different linkage methods produced significantly different cluster structures.
- Ward linkage generated the most balanced clusters.
- Hierarchical clustering effectively grouped similar customer behaviors.

## 📷 Project Visuals

<p align="center">
  <img src="images/complete_link_dendrogram.png" width="45%">
  <img src="images/ward_linkage_clusters.png" width="45%">
</p>

---

# 🛒 3. Market Basket Analysis

Applied association rule mining techniques to discover purchasing patterns in retail transaction data.

## 🛠 Techniques Used

- Apriori Algorithm
- Association Rules
- Frequent Itemset Mining
- Jaccard Similarity Analysis
- Correlation Analysis

## 📌 Key Insights

- Bakery, Juice, and Dairy were the most frequently purchased categories.
- Strong similarity relationships were identified between multiple product categories.
- Association rule mining revealed opportunities for product bundling and optimized product placement.

## 📷 Project Visuals

<p align="center">
  <img src="images/most_present_item_category.png" width="45%">
  <img src="images/jaccard_similarity_matrix_category.png" width="45%">
</p>

