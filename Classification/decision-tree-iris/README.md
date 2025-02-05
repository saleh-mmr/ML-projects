# Decision Tree Classification on the Iris Dataset  

## Project Overview  
This project applies **Decision Tree Classification** to the classic **Iris dataset** to classify flower species based on their sepal and petal measurements. The model is optimized using **Grid Search Cross-Validation** with different scoring metrics to find the best hyperparameters.  

## Technologies Used  
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

## Workflow  
1. **Prepare the Environment**  
   - Import necessary libraries  
   - Load the `iris.csv` dataset  

2. **Preprocess the Data**  
   - Split the dataset into features (`X`) and target (`y`)  
   - Split into training and testing sets  

3. **Train & Evaluate the Model**  
   - Train a **Decision Tree Classifier**  
   - Evaluate performance using `accuracy_score`  

4. **Hyperparameter Tuning**  
   - Perform **Grid Search Cross-Validation** using:  
     - `max_depth`  
     - `criterion` (`gini` or `entropy`)  
     - `class_weight` (balanced or none)  

5. **Visualization & Reporting**  
   - Generate **classification reports** for different scoring metrics  
   - Display the **confusion matrix** using `ConfusionMatrixDisplay`  

## Results  
The model is evaluated using multiple scoring metrics:  
- **Accuracy**  
- **Recall (Macro)**  
- **F1 Score (Macro)**  
- **Precision (Macro)**  

The best hyperparameters are selected based on these scores, and the confusion matrix is visualized.  

## Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/saleh-mmr/decision-tree-iris.git
   cd decision-tree-iris

2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn matplotlib

3. Run the script:
   ```bash
   jupyter notebook DecisionTree_Iris.ipynb
