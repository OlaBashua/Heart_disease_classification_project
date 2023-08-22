# Heart_disease_classification_project
Machine learning  Capstone Course project on heart disease classification
## Project outline
  ## Objective
I developed a machine learning model that analyzes patient's medical attributes and risk factors to determine if they are susceptible to a heart attack.

## Tasks

### Data Analysis
- Import the dataset and perform exploratory data analysis about the data 
- Get information about the dataset ( mean, max, min, quartiles, etc) 
- Find the correlation between all fields
  
### Data Visualization
- Visualize patients with and without heart disease  
- Visualize the age and heart disease of patients  
- Visualize the correlation between features using a heat map  

### Logistic Regression
- Build a simple logistic regression model  
- Evaluate accuracy using the confusion matrix  

### Decision Tree
- Build a decision tree model  
- Evaluate accuracy using the confusion matrix  
- Visualize the decision tree  

### Random Forest
- Build a Random Forest model  
- Evaluate accuracy using the confusion matrix  
- Visualize the model  

### Select the Best Model
- Compare confusion matrices  
- Print classification reports  
- Calculate Recall, Precision, and F1 scores  
- Visualize confusion matrices  
-  Select the best model based on the accuracy

 ## Technical Skills
In this project, I utilized a range of technical skills and tools to successfully accomplish the tasks:

- Data Analysis: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn
- Machine Learning Models: Logistic Regression, Decision Trees, Random Forest
- Model Evaluation: Scikit-Learn's metrics (confusion matrix, accuracy score, etc.)
- Graph Visualization: To visualize Decision Trees and Random Forests
These tools allowed me to efficiently process, analyze, visualize,  and model the heart disease dataset.

## Model Results

### Models and Accuracy:
  - Logistic Regression: Accuracy of 80.5%
  - Decision Tree: Accuracy of 97.1%
  - Random Forest: Accuracy of 99.0%

### Best Model:
-  Identified Random Forest as the best-performing model for heart disease classification.

### Insights:
  - Decision Tree achieved high precision, recall, and F1-score for both classes.
  - Random Forest demonstrated excellent precision, recall, and F1-score, indicating its effectiveness in classifying heart disease cases.

### Correlation Analysis:
  - Identified key predictors: "cp" (chest pain), "thalach" (maximum heart rate achieved), "exang" (exercise-induced angina), "oldpeak" (ST depression induced by exercise relative to rest), and "ca" (number of major vessels colored by fluoroscopy).
  - "Age" and "sex" showed moderate negative correlation with the target variable.

## Conclusion
The successful development and evaluation of the heart disease classification models. I compared their performance using accuracy, confusion matrices, and classification reports. Based on the results, I selected the best-performing model and demonstrated the effectiveness of machine learning techniques in identifying patients at risk of heart attacks. The project highlighted the significance of data analysis, visualization, and model selection in medical research. Through this project, I further harnessed my knowledge and skills in data preprocessing, model building, evaluation, and interpretation.

