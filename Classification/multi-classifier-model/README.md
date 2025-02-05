# Churn Prediction Model Comparison  

## Project Overview  
This project compares multiple classification models for predicting customer churn using the `churn-analysis.csv` dataset. The models are evaluated using different scoring metrics, and hyperparameters are optimized with GridSearchCV to find the best configurations.  

## Technologies Used  
- Python  
- Pandas  
- Scikit-learn  
- Seaborn  
- Matplotlib  

## Workflow  
1. **Data Preparation**  
   - Load the dataset (`churn-analysis.csv`)  
   - Separate features (`X`) and target (`y`)  

2. **Model Selection & Hyperparameter Tuning**  
   - Train multiple classifiers:  
     - Linear Perceptron  
     - K-Nearest Neighbors  
     - Decision Tree  
     - Random Forest  
     - AdaBoost  
     - Gaussian Naïve Bayes  
   - Optimize hyperparameters using **GridSearchCV**  
   - Evaluate models using different scoring metrics  

3. **Results Analysis**  
   - Print top-performing models for each scoring metric  
   - Display the **classification report**  
   - Visualize the **confusion matrix** for the best model  

## Scoring Metrics  
- **Accuracy**  
- **Precision (Macro)**  
- **Recall (Macro)**  
- **F1 Score (Macro)**  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/saleh-mmr/ML-projects.git
   cd ML-projects/churn_model_comparison

2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn seaborn matplotlib

3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook churn_model_comparison.ipynb  



## Author  

Saleh Mir Mohammad Rezaei
