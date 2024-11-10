# Crypto-Clustering

This project focuses on clustering cryptocurrencies using various unsupervised learning techniques. The goal is to understand the underlying patterns and group similar cryptocurrencies together based on their features.

## Project Overview

Cryptocurrencies have become a popular asset class, and their market dynamics are complex. This project leverages machine learning techniques, specifically clustering, to analyze the cryptocurrency market. By clustering similar cryptocurrencies together, we can gain insights into the market and identify trends that are not immediately obvious.

## Data

The dataset used in this project is `crypto_market_data.csv`, which contains various features of different cryptocurrencies. The data includes information such as market capitalization, volume, and prices.

### Data Source

- `crypto_market_data.csv`: This file contains the cryptocurrency market data used for clustering.

## Analysis

### Step 1: Preprocessing the Data

- **Normalization**: The data was normalized to ensure that all features contribute equally to the clustering process.
- **PCA (Principal Component Analysis)**: PCA was applied to reduce the dimensionality of the dataset and retain the most important features.

### Step 2: Clustering Cryptocurrencies

- **K-Means Clustering**: The K-Means algorithm was used to group cryptocurrencies into clusters. The elbow method was applied to determine the optimal number of clusters.
- **Hierarchical Clustering**: Hierarchical clustering was also explored as an alternative method to group cryptocurrencies.

### Step 3: Visualizing the Clusters

- **Scatter Plot**: A scatter plot was created to visualize the clusters in two dimensions using the first two principal components.
- **3D Plot**: A 3D plot was also created to visualize the clusters in three dimensions.

## Technologies Used

- **Python**: The programming language used for the entire analysis.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For implementing machine learning algorithms, including K-Means and PCA.
- **Matplotlib and Plotly**: For data visualization.
- **Jupyter Notebook**: For interactive coding and visualization.

## How to Use This Repository

1. **Clone the repository**:
    

2. **Navigate to the project directory**:
   
    cd Crypto-Clustering
    
3. **Ensure you have the necessary Python packages installed**:
    - Install the required packages:
      pip install -r requirements.txt
    

4. **Run the Jupyter Notebook**:
    - Launch Jupyter Notebook:
      jupyter notebook
    - Open the `Crypto_Clustering.ipynb` file and follow along with the analysis.

## Results

The project successfully segmented cryptocurrencies into distinct clusters, uncovering trends and relationships that add depth to market analysis and support potential strategic decision-making
