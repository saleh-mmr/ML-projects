# Customer Churn Prediction Using Multiple Classifiers  

## Project Overview  
This project implements various **classification models** to predict **customer churn** based on historical data. It uses **hyperparameter tuning** with `GridSearchCV` and evaluates models using different scoring metrics.  

## Technologies Used  
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Workflow  
1. **Load & Explore the Data**  
   - Import the `churn-analysis.csv` dataset  
   - Perform preliminary analysis  

2. **Data Preprocessing**  
   - Separate features (`X`) and target (`y`)  
   - Split data into training and testing sets  

3. **Model Training & Tuning**  
   - Implement multiple classifiers:  
     - Perceptron  
     - K-Nearest Neighbors  
     - Decision Tree  
     - Random Forest  
     - AdaBoost  
     - Naïve Bayes  
   - Optimize hyperparameters using **GridSearchCV**  
   - Use **Stratified K-Fold Cross-Validation**  

4. **Evaluation & Visualization**  
   - Compare models based on various scoring metrics:  
     - Accuracy  
     - F1 Score (Macro)  
     - Precision (Macro)  
     - Recall (Macro)  
   - Display confusion matrices for the best models  

## Results  
The best models for each scoring metric are selected and evaluated using classification reports and confusion matrices.  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/saleh-mmr/customer-churn-analysis.git
   cd customer-churn-analysis

2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
 
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook customer_churn_analysis.ipynb

## Author

Saleh Mir Mohammad Rezaei