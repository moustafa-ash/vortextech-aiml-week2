# Student Dropout Prediction with Logistic Regression

This project uses the cleaned student dataset from last week in [cleaned_student_dataset.csv](cleaned_student_dataset.csv) to build a binary classification model that predicts whether a student is more likely to be a Dropout or a Graduate.

The notebook first filters the dataset to remove rows labeled "Enrolled," leaving only the two outcomes required for a strict binary classification task. It then converts the target labels into numeric values and trains a Logistic Regression model. Finally, the notebook evaluates the model on a held-out test set and reports accuracy, precision, recall, and F1-score.

## What the project does
- Loads the dataset
- Removes the Enrolled rows to create a strict binary target
- Maps Dropout to 0 and Graduate to 1
- Trains a logistic regression model
- Evaluates the model with accuracy, precision, recall, and F1-score

## Model results
- Accuracy: 0.9201
- Precision: 0.9133
- Recall: 0.9621
- F1-score: 0.9371

## Requirements
Install the following Python packages:

```bash
pip install -r requirements.txt
```

## How to run
1. Open the notebook in Jupyter Notebook or VS Code with the Python/Jupyter extension.
2. Make sure the dataset file is in the same folder as the notebook.
3. Run all cells in order.

The notebook will print the model metrics and show the final summary.
