
# 🧠 Customer Segmentation using K-Means Clustering

This project implements **K-Means Clustering** to segment retail customers based on their purchasing behavior. By analyzing customer features such as **Age**, **Annual Income**, and **Spending Score**, we aim to identify distinct customer groups that can be targeted with personalized marketing strategies.

---

## 📋 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🧰 Technologies Used](#-technologies-used)
- [📂 Dataset](#-dataset)
- [⚙️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [📈 Steps Involved](#-steps-involved)
- [📊 Results](#-results)
- [📄 License](#-license)

---

## 📌 Project Overview

We apply **K-Means Clustering** on a dataset of mall customers to group them into clusters based on their:

- Age
- Annual Income (k$)
- Spending Score (1–100)

These segments help businesses better understand customer behaviors and make data-driven marketing decisions.

---

## 🧰 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📂 Dataset

The dataset used is the **Mall Customers Dataset** from Kaggle.  
It includes the following columns:

| Column Name           | Description                                      |
|-----------------------|--------------------------------------------------|
| `CustomerID`          | Unique customer identifier                       |
| `Gender`              | Customer gender (`Male` / `Female`)             |
| `Age`                 | Customer age                                     |
| `Annual Income (k$)`  | Annual income in thousands of dollars            |
| `Spending Score (1-100)` | A score assigned based on customer behavior |

🔗 **[Download Dataset from Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)**

---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
````

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🚀 Usage

Run the Jupyter Notebook or script:

```bash
python customer_segmentation.py
```

Or open and run the notebook:

```bash
jupyter notebook Customer_Segmentation_KMeans.ipynb
```

---

## 📈 Steps Involved

### 1. Data Loading

* Load dataset using `pandas`
* Preview first few rows and basic info

### 2. Preprocessing

* Drop unnecessary columns (e.g., `CustomerID`)
* Encode `Gender` as numeric
* Handle missing values (if any)

### 3. Feature Selection

* Select `Age`, `Annual Income (k$)`, and `Spending Score`

### 4. Scaling

* Normalize features using `StandardScaler`

### 5. Optimal Cluster Selection

* Use **Elbow Method** to determine the best value for `K`

### 6. K-Means Clustering

* Apply KMeans with selected `K`
* Predict and assign each customer to a cluster

### 7. Visualization

* Scatter plots to visualize customer clusters based on features
* Visualize centroids of each cluster

---

## 📊 Results

* ✅ **Optimal Clusters Identified** using the Elbow Method
* 📌 **Customer Clusters Created** with clear separation
* 📉 **Visual Representation** of clusters by Annual Income & Spending Score
* 📍 **Cluster Centers** calculated for interpreting segment behavior

Example Output:

* Cluster 0: High Income, High Spending
* Cluster 1: Low Income, Low Spending
* Cluster 2: High Income, Low Spending
* ...

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

* Dataset: [Mall Customers Dataset - Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)
* K-Means Clustering: [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/clustering.html#k-means)

---




