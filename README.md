# Business Data Clustering Dashboard 📊🔍

## Overview

The Business Data Clustering Dashboard is an advanced data analysis tool that leverages machine learning techniques to provide deep insights into your business data through intelligent clustering algorithms.

## 🌟 Key Features

- **Flexible Clustering Algorithms**
  - K-Means Clustering
  - DBSCAN Clustering
- **Automatic Hyperparameter Optimization**
  - Optimal cluster number selection
  - Intelligent epsilon value recommendation
- **Interactive Visualizations**
  - PCA 2D Projection
  - t-SNE Visualization
  - Cluster Size Distribution
- **Comprehensive Data Preprocessing**
  - Handles missing values
  - Scales numeric features
  - One-hot encodes categorical features

## 🛠 Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- Matplotlib
- Plotly

## 🚀 Installation

### Prerequisites
- Python 3.8+
- pip

### Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/business-clustering-dashboard.git

# Navigate to project directory
cd business-clustering-dashboard

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

## 📝 How to Use

1. Upload a CSV file
2. Choose clustering algorithm (K-Means or DBSCAN)
3. Adjust parameters if needed
4. Click "Train Model"
5. Explore visualizations and insights

## 🔍 Clustering Insights

The dashboard provides:
- Cluster size distribution
- 2D visualization (PCA and t-SNE)
- Cluster descriptions
- Top differentiating features

## 📊 Sample Visualizations

### Cluster Distribution
![Cluster Distribution](cluster_dist.png)

### PCA Visualization
![PCA Plot](pca_plot.png)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License

This project is licensed under the MIT License.
