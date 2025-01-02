# 🎯 Mall Customer Segmentation Analysis

> A machine learning project that segments mall customers into distinct groups based on their purchasing behavior and demographics using clustering algorithms.

![Python](https://img.shields.io/badge/python-v3.9+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-latest-orange.svg)
![Pandas](https://img.shields.io/badge/pandas-latest-green.svg)
![Seaborn](https://img.shields.io/badge/seaborn-latest-red.svg)

## 📊 Project Overview

This project analyzes mall customer data to identify distinct customer segments using unsupervised learning techniques. The segmentation helps understand customer behavior patterns and can be used for targeted marketing strategies.

## 🎯 Key Findings

We identified 5 main customer segments:

1. **Average Customers** (Cluster 0)
   - Age: ~43 years
   - Average income and spending
   - Potential for increased engagement

2. **High Income, Low Spenders** (Cluster 1)
   - Age: ~41 years
   - High annual income but low spending
   - Prime target for marketing initiatives

3. **Budget Conscious** (Cluster 2)
   - Age: ~45 years
   - Low income and spending
   - Potential for targeted promotions

4. **Young Spenders** (Cluster 3)
   - Age: ~25 years
   - Low income but high spending
   - High engagement, lower profitability

5. **Prime Customers** (Cluster 4)
   - Age: ~33 years
   - High income and spending
   - Most valuable segment

## 🛠️ Tech Stack

- **Python**: Core programming language
- **Scikit-learn**: K-Means and Hierarchical Clustering
- **Pandas**: Data manipulation
- **Matplotlib/Seaborn**: Visualization
- **Jupyter Notebook**: Development environment

## 📊 Dataset Features

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## 🔍 Analysis Pipeline

1. **Data Preprocessing**
   - Data cleaning
   - Feature scaling
   - Exploratory data analysis

2. **Clustering Analysis**
   - Age & Spending Score based clustering
   - Annual Income & Spending Score based clustering
   - Hierarchical clustering analysis

3. **Visualization**
   - Cluster plots
   - Dendrograms
   - Distribution analysis

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Jupyter Notebook
- Required packages: pandas, scikit-learn, numpy, matplotlib, seaborn

### Installation

```bash
# Clone repository
git clone <https://github.com/rakanalb/Mall_Customers_Segmentation_Clustering_Analysis.git>

# Install dependencies
pip install pandas scikit-learn numpy matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## 📈 Usage

1. Open the Jupyter notebook
2. Run cells sequentially to:
   - Load and explore the data
   - Perform clustering analysis
   - Visualize results

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
