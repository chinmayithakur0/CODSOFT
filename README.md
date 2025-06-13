# Titanic Survival Prediction 🚢

This project builds a machine learning model to predict survival outcomes of passengers on the Titanic using the famous Titanic dataset. It uses a Random Forest classifier along with data preprocessing steps such as encoding, imputing, and normalization.

## 📂 Files Included

- `titanic_survival_prediction.py`: The main Python script containing data loading, preprocessing, model training, evaluation, and visualization.
- `Titanic-Dataset.csv`: The dataset used for prediction (ensure this is included if sharing complete project).
- `requirements.txt`: Python libraries used in this project.
- `README.md`: Project overview and instructions.

## 🧠 Features Used

- Pclass
- Sex
- Age
- SibSp (number of siblings/spouses aboard)
- Parch (number of parents/children aboard)
- Fare
- Embarked

## 📈 Model

- **Algorithm**: Random Forest Classifier
- **Accuracy**: ~81%

## 🛠 How to Run

```bash
pip install -r requirements.txt
python titanic_survival_prediction.py
```

## 📊 Output

- Classification report
- Accuracy score
- Confusion matrix heatmap

## 📚 Libraries Used

- pandas
- scikit-learn
- matplotlib
- seaborn
