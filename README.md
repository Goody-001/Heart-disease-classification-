# Heart Disease Prediction with SVM  
This project applies a Support Vector Machine (SVM) classifier with a linear kernel to predict the presence of heart disease using clinical and physiological patient data.  

## Dataset  
The dataset used is the **Heart Disease UCI dataset**, which contains medical attributes such as age, cholesterol level, blood pressure, and more. The target variable indicates the presence (1) or absence (0) of heart disease.  

## Methodology  
1. **Exploratory Data Analysis (EDA):** Correlation heatmap used to study relationships between features and the target.  
2. **Data Preprocessing:** No feature scaling was applied.  
3. **Modeling:** Linear kernel SVM (Support Vector Machine) was implemented.  
4. **Evaluation:** Model performance assessed using accuracy, precision, recall, and F1-score.

## Results  
- The Linear SVM model achieved an **accuracy of 92%**.  
- Class 0: Precision = 0.88, Recall = 0.92, F1-score = 0.90  
- Class 1: Precision = 0.94, Recall = 0.92, F1-score = 0.93  
- Overall, the model demonstrated strong performance in predicting heart disease.

## License
This project is licensed under the MIT License.

## Conclusion  
The project demonstrated that a Linear SVM can effectively predict heart disease using the provided dataset, achieving high accuracy and balanced performance across classes. The results suggest that SVM is a reliable model for this classification task.  




