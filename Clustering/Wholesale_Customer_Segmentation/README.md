# Customer Segmentation Using Clustering Algorithms

## Project Overview
This project performs customer segmentation on a wholesale dataset using clustering algorithms such as K-Means, Agglomerative Clustering, and DBSCAN. It leverages data preprocessing techniques, including power transformation and MinMax scaling, to improve clustering effectiveness.

## Dataset
The dataset used is `Wholesale-customers-data.csv`, which contains customer purchasing behavior data. The `Channel` and `Region` columns are removed during preprocessing.

## Methods Used
- **Data Preprocessing:**
  - Dropped categorical columns (`Channel`, `Region`)
  - Applied Power Transformation for normalization
  - Used MinMaxScaler for feature scaling
- **Clustering Algorithms:**
  - K-Means (evaluated using inertia and silhouette scores)
  - Agglomerative Clustering (tested with different linkage methods)
  - DBSCAN (not yet implemented in the provided code)
- **Model Evaluation:**
  - Inertia (for K-Means)
  - Silhouette Score (for all clustering models)

## Requirements
To run the notebook, install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Results

- The optimal number of clusters for K-Means was determined using inertia and silhouette analysis.  
- Agglomerative clustering is set up to test different linkage methods.  

## Usage

1. Load the dataset and preprocess it.  
2. Apply clustering algorithms.  
3. Evaluate results using silhouette scores and inertia.  
4. Visualize the findings using plots.  

## Future Improvements

- Implement and compare DBSCAN clustering results.  
- Perform feature selection and PCA for dimensionality reduction.  
- Optimize hyperparameters for better clustering performance.  

## Author

**Saleh Mir Mohammad Rezaei**
