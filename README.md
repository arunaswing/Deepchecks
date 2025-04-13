# Deepchecks Movie Rating Classifier 🎬✅

This project uses [Deepchecks](https://deepchecks.com) to validate a machine learning model trained to classify whether a movie rating is positive, based on the MovieLens 100k dataset.

## 🔧 Tech Stack
- Python, Pandas
- Scikit-learn
- Deepchecks (tabular)

## 📂 Files
- `Deepcheck.ipynb`: Jupyter notebook with model + Deepchecks analysis
- `deepchecks_report.html`: Generated HTML report from Deepchecks
- `ratings.csv`, `movies.csv`, etc.: MovieLens data files
- `README.txt`: Info from original dataset
- `deepchecks_report.pdf`: Exported report with visuals

## 📊 Goal
Predict whether a user will rate a movie ≥ 4 using just `userId` and `movieId`, and run Deepchecks to analyze:

- Train-test drift
- Prediction degradation
- Baseline performance vs real model
- Inference time and feature stability


## 📜 Blog Post
🔗 [[Link to Medium post](https://medium.com/@agopi5/057811cf395d)]
