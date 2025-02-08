# Optimizing DBSCAN Clustering on Wholesale Customers Data

## Overview
This project demonstrates how to perform clustering on the Wholesale Customers dataset using the DBSCAN algorithm. The workflow includes data preprocessing, transformation, and scaling, followed by an extensive grid search to tune the DBSCAN parameters (`eps` and `min_samples`) based on the silhouette score.

## Features
- **Data Loading:** Reads the `Wholesale-customers-data.csv` file.
- **Preprocessing:**  
  - Separates categorical features (`Channel` and `Region`) from continuous ones.
  - Applies a PowerTransformer to stabilize variance in continuous features.
  - Scales the features using MinMaxScaler.
- **Clustering:**  
  - Uses DBSCAN to cluster the combined dataset.
  - Performs grid search over a range of `eps` and `min_samples` values.
  - Evaluates each configuration using the silhouette score.
- **Results:**  
  - Outputs the default DBSCAN parameters.
  - Stores the silhouette scores and number of clusters for each valid configuration in a DataFrame.

## Installation
To run this project, ensure you have Python 3.x installed. Install the required libraries using:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Place the Wholesale-customers-data.csv file in the same directory as the notebook.
2. Open the Jupyter Notebook:
```bash
jupyter notebook dbscan_wholesale_clustering.ipynb
```
3. Run the notebook cells to preprocess the data, perform clustering, and view the results.


## Data

- Dataset: Wholesale-customers-data.csv
This dataset contains information about wholesale customers which is used for clustering analysis.

## Author

**Saleh Mir Mohammad Rezaei**
