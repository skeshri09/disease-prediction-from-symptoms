# Disease Prediction from Symptoms

Machine learning project that predicts a disease from symptoms a user
selects in a desktop app. Published as a conference paper at IEEE ICESC 2023.

Paper: Strategic Analysis of Population Health Management using Machine Learning
DOI: https://doi.org/10.1109/ICESC57686.2023.10193171

## What it does
- The user enters a patient name and selects symptoms from dropdown menus
  (Tkinter interface)
- The user picks one of four models: Decision Tree, Random Forest,
  Naive Bayes or K-Nearest Neighbors
- The predicted disease is shown in the app and each prediction is saved
  to a local SQLite database

## Results
Accuracy reported in the paper:
| Model | Accuracy |
|---|---|
| K-Nearest Neighbors | 95% |
| Naive Bayes | 94.6% |
| Decision Tree | 94% |
| Random Forest | 92% |

## Data
The notebook reads training.csv and testing.csv, which are not included
in this repo.

## Tools
Python, scikit-learn, pandas, Tkinter, SQLite

## How to run
1. Install: pip install pandas scikit-learn matplotlib
2. Add your own training.csv and testing.csv next to the notebook
3. Open disease_prediction.ipynb and run the cells in order

## Authors
Surabhi Keshri, Nagarjuna Reddy, supervised by Ms. A. Benazir Begum
(Hindustan Institute of Technology and Science, Chennai)

For educational use only. Not a medical diagnosis tool.
