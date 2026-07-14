# VortexTech AI/ML Internship — Week 2: Build a Classification Model

## What this project does
Building on Week 1's cleaned Titanic dataset, this notebook:
- Identifies `Survived` as the binary target and prepares feature columns
- Encodes categorical features (`Sex`, `Embarked`) using one-hot encoding
  (with a side-by-side look at `LabelEncoder` for comparison)
- Splits data 80/20 into train/test sets (`random_state=42` for reproducibility)
- Trains and compares two models: **Logistic Regression** and **Decision Tree**
- Evaluates both with Accuracy, Precision, Recall, and F1-score, plus confusion matrices
- Interprets results and lists concrete next steps (GridSearchCV, SMOTE, feature engineering)

## How to run it
1. Clone this repo
2. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Launch Jupyter:
   ```
   jupyter notebook
   ```
4. Open `week2_classification.ipynb` and run all cells (`Cell > Run All`)

## Files
- `week2_classification.ipynb` — the full notebook (already executed, with outputs saved)
- `titanic.csv` — the dataset used (same as Week 1)

## Dataset source
Titanic dataset, publicly available on Kaggle ("Titanic - Machine Learning from Disaster").
