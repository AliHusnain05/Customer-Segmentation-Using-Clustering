# Customer-Segmentation-Using-Clustering 

## 📌 Project Overview  
This project applies *Unsupervised Learning (Clustering)* techniques to segment mall customers into different groups based on their demographics and spending behavior.  

The goal is to help businesses understand their customers better, create targeted marketing strategies, and improve customer experience.  

---

## 📊 Dataset  
- *Source*: [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- *Features*:  
  - CustomerID: Unique ID assigned to the customer  
  - Gender: Male/Female  
  - Age: Age of the customer  
  - Annual Income (k$): Annual income in thousands  
  - Spending Score (1-100): Score assigned based on customer behavior and spending nature  

---

## 🛠 Methodology  

### 1. Exploratory Data Analysis (EDA)  
- Checked missing values, distributions, and summary statistics.  
- Visualized customer demographics (age, income, spending score).  

### 2. Feature Scaling  
- Applied *StandardScaler/MinMaxScaler* to normalize the data for clustering.  

### 3. Clustering Models  
- *K-Means Clustering*  
  - Used *Elbow Method* and *Silhouette Score* to find the optimal number of clusters.
  
### 4. Visualization  
- Plotted clusters using *2D and 3D scatter plots*.  
- Compared cluster characteristics (income vs spending score, age groups, etc.).  

---

## 💡 Business Insights  
- Customers can be grouped into segments such as:  
  - *High Income – High Spending* → Premium customers, target for luxury products.  
  - *Low Income – High Spending* → Potentially impulsive buyers, target with discounts.  
  - *High Income – Low Spending* → Potential customers, need engagement strategies.  
  - *Low Income – Low Spending* → Least priority group.  

- Businesses can use these insights for:  
  - Targeted marketing campaigns.  
  - Personalized product recommendations.  
  - Customer retention strategies.  

---

## 🚀 Technologies Used  
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (KMeans, AgglomerativeClustering, StandardScaler)  
- Scipy (for dendrograms)  

---

## 📈 Results  
- K-Means identified *5 optimal clusters* based on income and spending score.  
- Hierarchical clustering produced similar segments, validating results.

---

## 🔮 Future Work  
- Apply *DBSCAN* for density-based clustering.  
- Use *PCA (Principal Component Analysis)* for dimensionality reduction.  
- Integrate clustering insights into a business dashboard.  

---

## 👩‍💻 Author  
Developed by "Rana Ali Husnain"  
📧 Contact: ranaalihusnain@gmail.com  
🔗 GitHub: https://github.com/AliHusnain05/  

---

---
