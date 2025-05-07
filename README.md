# 🧠 Customer Segmentation Using Unsupervised Learning

## 📌 Introduction  
In today’s competitive financial landscape, banks collect vast amounts of transactional data from customers. However, raw data alone cannot drive intelligent decision-making. This project leverages unsupervised learning techniques to uncover meaningful customer segments, helping banks tailor campaigns, enhance customer satisfaction, and build loyalty.

---

## ❓ Problem Statement  
Mass marketing campaigns across all customers are inefficient and expensive. To optimize outreach, the bank needs to identify segments of credit card users based on their transaction behaviors and key personal attributes, allowing for personalized deals and merchant partnerships.

---

## 🎯 Objective  
The goal is to:
- Understand transaction patterns across credit card users  
- Engineer meaningful features on the customer level  
- Cluster customers using unsupervised learning  
---

## 📊 Dataset Description  
Raw transaction-level data with attributes including:

| Column Name                | Description                                  |
|---------------------------|----------------------------------------------|
| `TransactionID`           | Unique transaction ID                        |
| `CustomerID`              | Unique customer ID                           |
| `CustomerDOB`             | Date of birth                                |
| `CustGender`              | Gender                                       |
| `CustLocation`            | Location                                     |
| `CustAccountBalance`      | Account balance (INR)                        |
| `TransactionDate`         | Date of transaction                          |
| `TransactionTime`         | Time of transaction (Unix timestamp)         |
| `TransactionAmount (INR)` | Amount of transaction                        |
| `OwnedProducts`           | Products owned by the customer               |


---

## ✅ Deliverables  
- Perform Exploratory Data Analysis (EDA)  
- Feature engineering and aggregation  
- Data cleaning and scaling  
- Apply clustering algorithms (K-Means, DBSCAN, HDBSCAN, etc.)  
- Evaluate models using Silhouette Score  
- Visualize and interpret resulting clusters  
- Provide business recommendations for each segment  

---

## 🧪 Clustering Models Evaluation (Silhouette Scores)

| Model                                 | Number of Clusters | Silhouette Score |
|--------------------------------------|--------------------|------------------|
| K-Means                              | 2                  | 0.387            |
| DBSCAN                               | 6                  | 0.272            |
| HDBSCAN                              | 8                  | 0.433            |
| Hierarchical Clustering              | 2                  | 0.403            |
| Spectral Clustering (with PCA)       | 8                  | **0.690** ✅ Best |
| Spectral Clustering (Original Features) | 8               | 0.393            |

---

## 🧠 Skills Demonstrated  
- 🧹 Data wrangling and cleaning  
- 🧾 Feature engineering and aggregation  
- 📐 Scaling and dimensionality reduction (PCA)  
- 📈 Unsupervised learning models  
- 📊 Cluster evaluation using Silhouette Score  
- 🧩 Business insights generation from clusters  

---

