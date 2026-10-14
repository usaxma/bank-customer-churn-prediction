# Bank Customer Churn Prediction

Predict which bank customers are likely to leave using the classic `Churn_Modelling` dataset. The notebook covers EDA, classical classifiers, and an **H2O AutoML** pass.

## Skills

- Banking tabular EDA (credit score, tenure, balance, products, salary)
- Binary classification and class mix
- Feature encoding for geography and gender
- Baseline models plus H2O AutoML
- Business framing: retain high-value customers

## Dataset

`Churn_Modelling.csv` is included (~10k customers). Target: `Exited` (1 = churned).

## Run

```bash
pip install -r requirements.txt
jupyter notebook Bank_Customer_Churn_Prediction.ipynb
```

## Structure

```
bank-customer-churn-prediction/
├── Bank_Customer_Churn_Prediction.ipynb
├── Churn_Modelling.csv
├── requirements.txt
└── README.md
```
