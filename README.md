# Titanic Survival Prediction using Logistic Regression

## Project Overview

This project uses **Logistic Regression**, a supervised machine learning classification algorithm, to predict whether a passenger survived the Titanic disaster.

The project is implemented in Python using a Jupyter Notebook. It includes data exploration, preprocessing, model training, predictions, and evaluation.

## Dataset

The project uses the Titanic dataset loaded from Seaborn:

```python
sns.load_dataset("titanic")
```

The dataset contains passenger information and the target column `survived`, which indicates whether a passenger survived.

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## Project Workflow

1. Load the Titanic dataset.
2. Explore the dataset using its columns, preview, and information.
3. Remove selected columns that are not used in the model.
4. Handle missing values and prepare the data.
5. Encode categorical features such as `sex` and `embarked` using `LabelEncoder`.
6. Separate the features (`X`) and target (`y`).
7. Split the data into training and testing sets.
8. Train a Logistic Regression model.
9. Generate predictions on the test data.
10. Evaluate the model using accuracy, a confusion matrix, and a classification report.

## Model Evaluation

The notebook uses the following Scikit-learn metrics:

- **Accuracy Score** — measures the proportion of correct predictions.
- **Confusion Matrix** — summarizes correct and incorrect classifications.
- **Classification Report** — provides precision, recall, F1-score, and support.

## How to Run

1. Clone or download this repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Install the required libraries:

   ```bash
   pip install numpy pandas seaborn matplotlib scikit-learn jupyter
   ```

4. Open `Logistic_regression.ipynb` in Jupyter Notebook.
5. Run the notebook cells in order.

> The notebook loads the Titanic dataset through Seaborn, so an internet connection may be needed the first time the dataset is fetched.

## Project Structure

```text
.
└── Logistic_regression.ipynb
```

## Learning Outcomes

- Understanding a supervised classification problem.
- Exploring and preparing a dataset with Pandas.
- Encoding categorical variables.
- Splitting data into training and testing sets.
- Training a Logistic Regression model.
- Evaluating classification results using Scikit-learn.

## Author

**Izaan Ansari**
