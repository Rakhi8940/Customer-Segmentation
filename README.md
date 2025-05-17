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

customer-segmentation/
├── data/
│ └── customers.csv # Customer dataset
├── notebooks/
│ └── customer_segmentation.ipynb # Data analysis and clustering
├── app/
│ ├── templates/
│ │ └── index.html # (Optional) Web interface
│ ├── app.py # (Optional) Flask app
├── outputs/
│ └── cluster_plots/ # Cluster images/graphs
├── requirements.txt
└── README.md # Project documentation

yaml
Copy
Edit

---

## 📊 Evaluation Methods

- **Elbow Method**: Helps select the optimal number of clusters based on inertia.
- **Silhouette Score**: Measures how similar a data point is to its own cluster vs other clusters.

---

## 📄 Requirements

Install the required libraries with:

bash
pip install -r requirements.txt
Typical requirements.txt content:

txt
Copy
Edit
pandas
numpy
matplotlib
seaborn
scikit-learn
plotly
flask

---

## 💡 Future Enhancements

🎯 Dashboard: Integrate visualizations with a full web dashboard (e.g., using Streamlit or Dash)
🛍️ Real Business Data: Apply the model to real e-commerce or CRM data
📈 Cluster Profiling: Add cluster statistics to label groups (e.g., "High-Value Young Shoppers")
🔄 Automation: Create a script to retrain the model with new customer data

---

## 👩‍💻 Author

Developed by Rakhi Yadav
For feedback, collaboration, or questions

---
