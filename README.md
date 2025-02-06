
# **Customer Segmentation Using K-Means Clustering**

## **📌 Project Overview**
Customer segmentation is a crucial aspect of business analytics that helps companies understand their customers better and develop targeted marketing strategies. In this project, we use **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their **Annual Income** and **Spending Score**.

## **📊 Dataset Information**
- The dataset contains information about **200 customers** from a shopping mall.
- Features used for segmentation:
  - **Annual Income (in k$)**
  - **Spending Score (1-100)**
  - **Customer ID**
  - **Gender**
  - **Age**

## **🛠️ Tech Stack & Libraries Used**
- **Python**
- **Pandas** – for data manipulation
- **Matplotlib & Seaborn** – for data visualization
- **Scikit-Learn** – for machine learning (K-Means Clustering)

## **📌 Project Workflow**

### 1️⃣ **Data Collection & Preprocessing**
- Loaded the dataset into a Pandas DataFrame.
- Checked for missing values and cleaned the data.
- Selected the relevant features (**Annual Income** & **Spending Score**) for clustering.

### 2️⃣ **Finding Optimal Clusters**
- Used the **Elbow Method** to determine the best number of clusters.
- Plotted the **WCSS (Within-Cluster Sum of Squares)** values for different cluster counts.

### 3️⃣ **Applying K-Means Clustering**
- Trained the K-Means model on the dataset.
- Assigned each customer to a **cluster based on their spending behavior**.

### 4️⃣ **Visualizing the Clusters**
- Created scatter plots to visualize customer groups.
- Plotted **cluster centroids** to analyze customer segmentation.

## **📈 Results & Insights**
- Customers were successfully segmented into **5 distinct groups** based on their spending patterns.
- Identified **high-spending premium customers** and **low-income budget-conscious customers**.
- These insights help businesses optimize marketing strategies and improve customer engagement.


