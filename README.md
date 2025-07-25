# 🎯 Customer Segmentation using K-Means Clustering

This project applies **unsupervised machine learning** to perform customer segmentation using the **K-Means Clustering** algorithm. Leveraging the Mall Customers dataset, the goal is to group customers into distinct clusters based on their **Annual Income** and **Spending Score**, providing actionable insights for data-driven marketing and business strategy.

---

## 📁 Dataset Overview

The dataset used in this project is the popular **Mall_Customers.csv**, which contains 200 customer records with the following features:

| Column Name             | Description                                      |
|-------------------------|--------------------------------------------------|
| `CustomerID`            | Unique identifier for each customer              |
| `Gender`                | Customer's gender (Male/Female)                  |
| `Age`                   | Age of the customer (in years)                   |
| `Annual Income (k$)`    | Estimated yearly income (in $1000s)              |
| `Spending Score (1-100)`| Score assigned based on spending behavior        |

---

## 📌 Project Objectives

- Explore and preprocess customer data  
- Use **K-Means Clustering** to identify distinct customer groups  
- Visualize and interpret clusters to derive meaningful business insights  
- Recommend strategies for targeted marketing based on cluster characteristics  

---

## 🚀 Tech Stack

- **Language**: Python 🐍  
- **Libraries**:  
  - `pandas`, `numpy` – Data manipulation  
  - `matplotlib`, `seaborn` – Data visualization  
  - `scikit-learn` – Clustering (KMeans), Preprocessing  

---

## 🔍 Workflow

1. **Data Exploration & Cleaning**
   - Checked for missing values and performed summary statistics
   - Visualized distributions and pairwise relationships

2. **Feature Selection**
   - Focused on `Annual Income` and `Spending Score` for clustering

3. **Finding Optimal Clusters (k)**
   - Used **Elbow Method** to determine the best number of clusters
   - Found that **k = 5** gives the most interpretable and distinct segments

4. **K-Means Clustering**
   - Applied K-Means and labeled each customer with a cluster ID
   - Visualized clusters using 2D scatter plots for interpretation

5. **Cluster Interpretation**
   - Analyzed characteristics of each segment to draw marketing insights

---

## 📊 Cluster Insights

| Cluster | Income Level | Spending Behavior | Description                          |
|-------- |--------------|-------------------|--------------------------------------|
| 1       | Moderate     | Moderate          | Balanced regular customers           |
| 2       | High         | Low               | Cautious or brand-conscious spenders |
| 3       | Low          | Low               | Less engaged or budget buyers        |
| 4       | High         | High              | Premium customers, high-value group  |
| 5       | Low          | High              | Impulsive or deal-seeking customers  |

These insights can guide **personalized campaigns, loyalty programs, and budget allocation**.

---

## 📈 Final Visualization

The final scatter plot clearly shows five distinct clusters based on income and spending, helping us interpret customer behavior and segment strategies visually.

---

## 💡 Future Enhancements

- Use more features like Age, Gender, or Online Behavior for richer segmentation  
- Apply other clustering techniques such as **DBSCAN** or **Hierarchical Clustering**  
- Integrate **PCA** for better visualization of multi-dimensional clustering  
- Deploy as a real-time dashboard for marketing teams

---

## 🙌 Acknowledgements

This project was built as a part of hands-on learning in machine learning and unsupervised algorithms.  
Special thanks to the open-source community and contributors who provided access to the dataset.

---

## 📬 Contact

📧 Ritam Bhattacharya  
🔗 [LinkedIn](https://www.linkedin.com/) (www.linkedin.com/in/ritambhatt)  

---

> ⭐ If you liked this project or found it useful, feel free to star ⭐ this repository or fork 🍴 it to contribute!
