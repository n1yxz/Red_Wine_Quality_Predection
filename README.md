# Red_Wine_Quality_Prediction

A machine learning project that predicts the quality of red wine based on its physicochemical attributes. The project uses regression models to estimate wine quality scores from a dataset sourced from UCI Machine Learning Repository.

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

---

## 🧾 Introduction

This project aims to predict the quality of red wine using regression techniques based on its chemical properties. The model helps wine producers or quality control teams assess wine quality more efficiently and accurately.

---

## 📦 Dataset

- **File**: `winequality-red.csv`
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Records**: 1,599 rows × 12 columns
- **Target Variable**: `quality` (integer score from 0 to 10)

---

## 📊 Features

Each row represents a wine sample with the following features:

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target)

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/n1yxz/Red_Wine_Quality_Prediction.git
cd Red_Wine_Quality_Prediction
pip install -r requirements.txt
```
If requirements.txt is not present, manually install:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
🚀 Usage
Run the notebook using Jupyter:
```

jupyter notebook Updated_Red_Wine_Quality_Prediction.ipynb
Or execute the script (if converted):

```bash
python predict_wine_quality.py
```
🧠 Models
This project uses the following regression models:

Linear Regression

Random Forest Regressor

📈 Evaluation
The models are evaluated using:

R² Score

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

📊 Visualizations
Correlation heatmaps

Feature importance plots

Actual vs Predicted value comparisons

Distribution and box plots

🧪 Examples
Example output after model training:

```yaml
Random Forest Regressor:
R² Score: 0.65
MSE: 0.31
MAE: 0.45
```

🛠 Troubleshooting
Ensure the CSV file is in the same directory as the notebook.

Use pip install to resolve any missing module errors.

For Jupyter issues, try running: jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10

👨‍💻 Contributors
@n1yxz

📄 License
This project is open-source and available under the MIT License.

yaml
Copy code

---

Would you like me to export this as a downloadable `README.md` file for you?
