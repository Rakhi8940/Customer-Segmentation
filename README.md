<p align="center">
  <img src="https://github.com/user-attachments/assets/119818d1-dfdf-4efa-99da-acf941307dba" width="280" alt="Credit Card Fraud Detection Banner" style="margin: 10px; border-radius: 12px;">
  <img src="https://github.com/user-attachments/assets/e78307cb-4e50-4e94-8f7f-ea753c2d679e" width="280" alt="Second Banner" style="margin: 10px; border-radius: 12px;">
</p>

# 🧠 Customer Segmentation – Unsupervised Learning Project

This project applies **unsupervised machine learning** techniques to segment customers based on their purchasing behavior and demographic characteristics. By understanding customer segments, businesses can develop targeted marketing strategies and improve customer satisfaction.

---

## 🎯 Objective

- Identify distinct customer groups using clustering algorithms
- Analyze spending patterns and behavioral traits across segments
- Enable targeted marketing and personalization using cluster insights

---

## 📂 Dataset

- **Source**: [Kaggle Mall Customers Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial) or similar
- **Features**:
  - `CustomerID`: Unique customer identifier
  - `Gender`: Male/Female
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Income level
  - `Spending Score (1-100)`: Score assigned by the store based on customer behavior

> 📌 Place the dataset in the `data/` directory as `customers.csv`.

---

## 🚀 Project Workflow

1. **Data Preprocessing**
   - Load the dataset and check for missing or duplicated values
   - Encode categorical features (e.g., `Gender`)
   - Scale numerical features to normalize the data for clustering

2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions of age, income, and spending score
   - Use scatter plots and pair plots to understand relationships

3. **Clustering**
   - Apply clustering algorithms:
     - **K-Means Clustering**
     - Optional: DBSCAN, Hierarchical Clustering
   - Use **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters

4. **Segment Analysis**
   - Interpret each cluster and label customer segments
   - Compare characteristics across clusters (e.g., high income vs low spending)

5. **Visualization**
   - Visualize clusters in 2D using PCA or t-SNE
   - Plot income vs spending colored by clusters

6. **Optional: Web Page Integration**
   - Create a simple **HTML/CSS web page** to present cluster statistics and visualizations
   - Allow users to explore cluster insights interactively

---

## 🛠️ Technologies Used

| Technology      | Purpose                                       |
|------------------|-----------------------------------------------|
| pandas           | Data loading and manipulation                |
| numpy            | Numerical operations                         |
| matplotlib       | Visualization (scatter, bar, elbow plots)    |
| seaborn          | Advanced visualizations                      |
| scikit-learn     | Clustering algorithms and preprocessing       |
| plotly (optional)| Interactive cluster plots                    |
| flask (optional) | Serve visualizations via HTML page           |
| HTML/CSS         | Presenting insights through static web pages |

---

## 📁 Project Structure

```
customer-segmentation/
├── data/
│   └── customers.csv
├── notebooks/
│   └── customer_segmentation.ipynb
├── app/
│   ├── templates/
│   │   └── index.html
│   ├── app.py
├── outputs/
│   └── cluster_plots/
├── requirements.txt
└── README.md
```

---

## 📊 Evaluation Methods

- **Elbow Method**: Helps select the optimal number of clusters based on inertia.
- **Silhouette Score**: Measures how similar a data point is to its own cluster vs other clusters.

---

## 📄 Requirements

Install the required libraries with:

```bash
pip install -r requirements.txt
```

Sample `requirements.txt`:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
plotly
flask
```

---

## 📊 Example Visuals

<p align="center">
  <img src="https://github.com/user-attachments/assets/1a199a1b-188f-4d42-ba0f-02366a964bcb" width="500" alt="Credit Card Fraud Detection Banner" style="margin:8px; border-radius:8px;">
  <img src="https://github.com/user-attachments/assets/8b9c0e20-4b13-4836-8c1f-d505f7e27a43" width="500" alt="Credit Card Fraud Detection Banner" style="margin:8px; border-radius:8px;">
  <img src="https://github.com/user-attachments/assets/d616ebe5-9365-4802-b85a-4219974c9af9" width="500" alt="Credit Card Fraud Detection Banner" style="margin:8px; border-radius:8px;">
  <img src="https://github.com/user-attachments/assets/2a635995-317b-4cda-af4e-a41b8d56961d" width="500" alt="Credit Card Fraud Detection Banner" style="margin:8px; border-radius:8px;">
</p>

---

## 👩‍💻 Author

Developed by Rakhi Yadav  
For feedback, collaboration, or questions

---
