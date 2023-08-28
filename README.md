# CryptoClustering
# Cryptocurrency Clustering and Analysis

This project utilizes K-means clustering and Principal Component Analysis (PCA) to analyze and group cryptocurrencies based on their market data. It explores patterns and relationships within the data to identify clusters of similar cryptocurrencies.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Clustering Analysis](#clustering-analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In this project, we aim to:

- Load cryptocurrency market data from a CSV file.
- Normalize the data using StandardScaler.
- Determine the optimal number of clusters using the Elbow method.
- Apply K-means clustering to group cryptocurrencies.
- Visualize the results using scatter plots.
- Perform dimensionality reduction using PCA.
- Find the optimal number of clusters after dimensionality reduction.
- Reapply K-means clustering with PCA data.
- Visualize the final clustering results.

## Data Preparation

We start by loading cryptocurrency market data from a CSV file and normalizing it using `StandardScaler`. This step ensures that all features have the same scale, which is necessary for K-means clustering.

## Exploratory Data Analysis

We generate summary statistics and plot line charts to understand the data better. This helps us gain insights into the characteristics of cryptocurrencies.

## Clustering Analysis

We perform clustering analysis in two steps:

1. **Clustering with Original Data:** We determine the optimal number of clusters (k) using the Elbow method and apply K-means clustering to the original data.

2. **Clustering with PCA Data:** We reduce the dimensionality of the data using PCA and repeat the clustering process to find the optimal k after dimensionality reduction.

## Results

We present the clustering results visually using scatter plots. Each point represents a cryptocurrency, and the color indicates its cluster.

## Conclusion

In this project, we successfully clustered cryptocurrencies based on their market data. We found that dimensionality reduction with PCA improved the clustering results. The optimal number of clusters was determined using the Elbow method.

## Usage

To run this project, you'll need Python and the following libraries:

- Pandas
- hvPlot
- scikit-learn

Clone the repository and execute the Jupyter Notebook to replicate the analysis.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, please open an issue or submit a pull request.

