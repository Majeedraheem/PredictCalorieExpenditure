# 🏋️‍♂️ 2025 Kaggle Playground Series – Calorie Burn Prediction

Welcome to my solution for the [2025 Kaggle Playground Series – Calorie Burn Prediction](https://www.kaggle.com/competitions)! This competition is part of Kaggle’s monthly playground series, offering approachable datasets for practicing machine learning skills.

## 🎯 Competition Objective

Your goal is to **predict the number of calories burned during a workout** based on various physiological and activity-related features.

### 🧠 Problem Type
- **Regression Problem**
- **Evaluation Metric**: Root Mean Squared Logarithmic Error (RMSLE)

RMSLE = sqrt( (1/n) * ∑[log(pred + 1) - log(actual + 1)]² )


Where:
- `pred` is the predicted calorie value
- `actual` is the actual calorie value
- `n` is the number of observations

---

## 📁 Files Provided

| File Name              |    Description                                                  |
|------------------------|-----------------------------------------------------------------|
| `train.csv`            | Training data with features and target variable (`Calories`)    |
| `test.csv`             | Test data to predict `Calories`                                 |
| `sample_submission.csv`| Template for the submission format                              |

---

## 🧪 Data Source

The dataset was generated using a deep learning model trained on the original **Calories Burnt Prediction** dataset. While the distributions are similar, they are **not identical**. You are encouraged to:
- Compare this dataset with the original
- Experiment with using the original dataset for training or data augmentation

---

## 📌 Submission Format

The final submission should be a `.csv` file with the following format:
id,Calories
750000,93.2
750001,27.42
750002,103.8


## 🛠 Tools Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM
- Seaborn & Matplotlib
- Jupyter Notebooks
