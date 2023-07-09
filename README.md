# Titanic Survival Prediction Using Machine Learning

This project focuses on predicting the survival chances of Titanic passengers based on their sex, age, and other factors. The classification task is accomplished using the Random Forest algorithm.

## Dataset

The dataset for this project can be obtained from the Kaggle website. Download the dataset from the following link: [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data?select=train.csv). Once downloaded, the dataset is divided into three CSV files: `gender_submission.csv`, `train.csv`, and `test.csv`.

## Installation and Setup

To run the code, make sure you have the following libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:

```
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository and navigate to the project directory.
2. Run the Jupyter Notebook or Python script containing the code.
3. Ensure that the dataset files (`train.csv` and `test.csv`) are in the same directory as the code.
4. The code will train the Random Forest model and make predictions on the test data.
5. The predictions will be saved in a CSV file named `resultfile.csv`.
