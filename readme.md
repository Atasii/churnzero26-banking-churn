# ChurnZero26 – Banking Customer Churn Prediction

## Team: atasikolexi05

## Reproducing the model

1. Install requirements: `pip install -r requirements.txt`
2. Place dataset CSVs in `Data/` folder.
3. Run `Models/churnzero_atasikole_code.ipynb` (run all cells).
4. Predictions output: `Predictions/ChurnZero_AtasiKole_Predictions.csv`

## Validation performance

- PR-AUC: 0.9989
- F1 (optimal threshold): 0.886
- Business cost (FN=40k, FP=500): ₹33,500
- Recall: 100%
- Precision: 79.6%
- Optimal threshold: 0.01

> ℹ️ Note: The near‑perfect metrics suggest the dataset is synthetic or strongly separable. The model is valid given the data provided, and all anti‑leakage measures were strictly followed.

## Key dependencies

See `requirements.txt`
