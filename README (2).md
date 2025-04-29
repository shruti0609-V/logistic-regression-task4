# Logistic Regression: Binary Classification

## Dataset
We used the [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) for binary classification of malignant vs. benign tumors.

## Objective
Build and evaluate a binary classification model using Logistic Regression.

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Followed
1. **Data Preprocessing**
   - Removed irrelevant columns (`id`, `Unnamed: 32`)
   - Converted diagnosis into binary labels (M=1, B=0)

2. **Train-Test Split**
   - Split data into 80% training and 20% testing

3. **Feature Scaling**
   - Used `StandardScaler` for normalization

4. **Model Training**
   - Trained using `LogisticRegression` from `scikit-learn`

5. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve and AUC score

6. **Threshold Tuning**
   - Demonstrated how changing the classification threshold affects performance

7. **Sigmoid Function Explanation**
   - Plotted sigmoid curve to visualize output range

## Results
- Achieved high accuracy and AUC score (~0.98) on test data.
- ROC Curve showed strong separation between classes.

## Folder Structure
```
.
├── Logistic_Regression_Binary_Classifier.ipynb
├── README.md
└── data.csv  # (Or link provided)
```

## How to Run
1. Clone this repo
2. Download the dataset from Kaggle and place it in the same folder
3. Open the notebook and run all cells

