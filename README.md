# Fake News Predictor

A machine learning-based project that classifies news headlines or text as **Fake News** or **Not A Fake News** using multiple models including Logistic Regression, Random Forest, and Gradient Boosting using this [Kaggle dataset](https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection/data?select=true.csv).

## Features

- Text cleaning and preprocessing
- TF-IDF vectorization
- Training with:
  - Logistic Regression (LR)
  - Random Forest Classifier (RFC)
  - Gradient Boosting Classifier (GBC)
- Manual news classification via user input
- Simple interface for model comparison

## Models Used

| Model                  | Purpose                     |
|------------------------|-----------------------------|
| Logistic Regression    | Baseline linear classifier  |
| Random Forest Classifier | Ensemble decision trees     |
| Gradient Boosting Classifier | Advanced ensemble boosting  |

## Requirements

Install the required packages via pip:

```bash
pip install -r requirements.txt
```

## Files
FakeNewsPredictor.ipynb — Main notebook

README.md — This file

requirements.txt — Python dependencies

## How to Run
In a Jupyter notebook or Colab:

Clone the repository or upload the notebook.

Load the dataset (make sure it includes labeled fake and real news text).

Run all cells to train models.

Use the manual_testing() function to classify custom news strings.

---

## Input/Output Example

```bash
(Reuters) - A gift-wrapped package addressed to U.S. Treasury Secretary Steven Mnuchin’s home in a p...

===== PREDICTIONS =====
Logistic Regression (LR): Not A Fake News
Gradient Boosting Classifier (GBC): Not A Fake News
Random Forest Classifier (RFC): Fake News
```

## Output Labels
```bash
Fake News → 0

Not A Fake News → 1
```


