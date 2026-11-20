# Loan Default Predictor (ANOP 330 demo)

A small Streamlit web app that predicts whether a loan customer is likely to default. You enter home ownership, annual income, debt-to-income ratio and FICO score, and it shows the predicted default probability and class.

Team: Justin Verlin and Martin Lorinkov

This is our ANOP 330 ML web app class demo, built from Prof. Matt Bailey's example repo: https://github.com/MattDBailey/ANOP330Module_LoanDefaultPredictor-Streamlit

## Files

- `app.py`: the Streamlit app
- `model.pkl`: the saved model, loaded with pickle
- `requirements.txt`: Python packages
- `LoanDefault_ModelCREATE_SAVE.ipynb` and `LendingClub_DataSet.csv`: how the model was trained

## Run locally

```
pip install -r requirements.txt
streamlit run app.py
```
