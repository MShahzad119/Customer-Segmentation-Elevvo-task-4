# 🛍️ Customer Segmentation using K-Means

This repository contains my **Task 4 of Elevvo Internship**, where I performed **Customer Segmentation** on the **Mall Customers Dataset** using **Unsupervised Machine Learning (K-Means Clustering)**.

---

## 📌 Project Overview
Customer segmentation is an important business strategy that helps companies group customers based on behavior and preferences.  
In this project, we used **Annual Income** and **Spending Score** to segment mall customers into distinct groups.  

---

## ⚙️ Steps Performed
1. **Data Loading & Exploration**  
   - Loaded `Mall_Customers.csv` dataset from Kaggle  
   - Checked data structure and missing values  

2. **Preprocessing & Scaling**  
   - Selected `Annual Income (k$)` and `Spending Score (1-100)`  
   - Prepared data for clustering  

3. **Elbow Method**  
   - Determined the optimal number of clusters (k=5)  

4. **K-Means Clustering**  
   - Applied clustering on the dataset  
   - Assigned each customer a cluster label  

5. **Visualization**  
   - 2D scatter plot of clusters  
   - Cluster centroids highlighted  

6. **Cluster Analysis**  
   - Analyzed average spending and income for each group  

---

## 📊 Results
- **Optimal clusters = 5**  
- Identified customer segments:
  - **High Income – High Spending**  
  - **High Income – Low Spending**  
  - **Low Income – High Spending**  
  - **Low Income – Low Spending**  
  - **Moderate Income – Moderate Spending**

These insights can be used for **targeted marketing strategies**.

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Repository Structure
