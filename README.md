# Shipment Delay Predictor

A binary classification ML project to predict whether an e-commerce shipment will be delivered late.

## Dataset
- 10,999 shipment records from Kaggle
- Features: warehouse block, shipping mode, customer rating, discount, weight, and more

## Models Trained
| Model | Accuracy |
|---|---|
| Logistic Regression | 63.41% |
| Decision Tree | 65.36% |
| Random Forest | 66.68% |

## Evaluation (Random Forest)
- Precision: 76%
- Recall: 64%
- F1 Score: 70%

## Tech Stack
- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## How to Run
pip install -r requirements.txt
jupyter notebook