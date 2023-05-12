# CryptoClustering


# Cryptocurrency Market Analysis
This is a Python project that aims to analyze the performance of different cryptocurrencies in the market based on their price changes over a certain period of time. The data is sourced from a CSV file, which contains the daily price change percentage of various cryptocurrencies.

## Project Structure
The project consists of the following files:

- crypto_market_data.csv: This is the CSV file containing the market data.
- crypto_market_analysis.ipynb: This is the Jupyter notebook file containing the Python code for the analysis.
- README.md: This is the file you are currently reading, which provides an overview of the project.
## Dependencies
The following libraries are required to run the Python code in the Jupyter notebook:

- pandas
- hvplot
- scikit-learn
## Usage
To use this project, follow these steps:

- Clone the repository to your local machine.
- Open the Jupyter notebook `crypto_market_analysis.ipynb`.
- Run the cells in the notebook to load the data, preprocess it, and perform the analysis.
- Visualize the results using the plots generated by the code.
## Analysis
The analysis includes the following steps:

- Load the data from the CSV file into a Pandas DataFrame.
- Generate summary statistics to get an overview of the data.
- Visualize the data using a line plot to see the trends over time.
- Normalize the data using the `StandardScaler()` module from scikit-learn.
- Perform principal component analysis (PCA) to reduce the dimensionality of the data.
- Use the elbow method to determine the optimal number of clusters for K-means clustering.
- Cluster the data using K-means clustering.
- Visualize the clusters using a scatter plot.
## Conclusion
This project provides insights into the performance of different cryptocurrencies in the market based on their price changes over time. The analysis includes data preprocessing, dimensionality reduction, and clustering to identify patterns in the data. The results can be used to make informed decisions about investing in cryptocurrencies.
