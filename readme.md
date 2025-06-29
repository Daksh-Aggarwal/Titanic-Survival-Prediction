# Titanic Survival Prediction (Machine Learning Project)

This project predicts the survival of passengers aboard the Titanic using various machine learning models. It involves data preprocessing, model training, performance evaluation, and final prediction submission.


## Dataset Used

- **train.csv**: Training data with survival labels  
- **test.csv**: Test data for final prediction  
- **Source**: Kaggle


## Technologies & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn


## Data Preprocessing

- Filled missing values:
  - Age → Median value (29)
  - Embarked → Most frequent value ('S')
  - Fare in test set → Median
- Dropped irrelevant columns: `Name`, `Ticket`, `Cabin`
- Encoded categorical features (`Sex`, `Embarked`) using `LabelEncoder`


## Models Used

| Model                      | Abbreviation |
|----------------------------|--------------|
| Logistic Regression        | LR           |
| Random Forest Classifier   | RF           |
| Decision Tree Classifier   | DT           |
| Support Vector Classifier  | SVM          |
| K-Nearest Neighbors        | KNN          |
| Gaussian Naive Bayes       | NB           |


## Evaluation Metrics

- **Accuracy**: Overall prediction correctness  
- **AUC Score**: Area Under the ROC Curve  
- **Confusion Matrix**: TP/FP/TN/FN analysis  
- **ROC Curve**: True vs. False Positive Rates

---

## Visualization Highlights

- Bar Chart: Accuracy & AUC comparison for all models  
- ROC Curves: All models plotted in one graph  
- Confusion Matrices: Individual heatmaps for each model


## Best Performing Model

- **Random Forest Classifier** showed the highest accuracy and AUC.  
- It was selected for making final predictions on the test dataset.


## Output

- Predictions were saved to `submission.csv` with columns:
  - `PassengerId`
  - `Survived`


## 🡩‍💻 Author

Made by [**Daksh Aggarwal**](https://github.com/Daksh-Aggarwal), [**Anushka Verma**](https://github.com/anushka-verma-CODES), and [**Vemula Manvi Smaran**](https://github.com/manvi-smaran).

## 📄 License

This project is licensed under the MIT License.
