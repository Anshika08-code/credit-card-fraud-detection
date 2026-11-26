# Credit Card Fraud Detection

## What this does
Compares four classifiers (KNN, Logistic Regression, Decision Tree, Random Forest)
on the Kaggle credit card fraud dataset (284,807 transactions, 492 frauds).

## Results (held-out test set, 96 frauds)
| Model | Sensitivity | F1 |
| KNN (k=10) | 68.75% | 0.733 |
| Random Forest | 63.54% | 0.689 |
| Logistic Regression | 52.08% | 0.625 |
| Decision Tree | 58.33% | 0.615 |

## How to run
1. Download `creditcard.csv` from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
2. Create a folder called `data` next to the `code` folder and put the CSV in it.
3. Install the libraries: `pip install -r requirements.txt`
4. Open `code/credit_card_fraud_detection.ipynb` in Jupyter and choose Kernel > Restart & Run All.

## Dataset
Not included because of its size (about 150 MB). Download it from Kaggle (link above).
