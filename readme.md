# ChurnZero26 – Banking Customer Churn Prediction

## Team: atasikolexi05

## Reproducing the model

1. Install requirements: `pip install -r requirements.txt`
2. Place dataset CSVs in `Data/` folder.
3. Run `Models/churnzero_atasikole_code.ipynb` (run all cells).
4. Predictions output: `Predictions/ChurnZero_AtasiKole_Predictions.csv`

## Validation performance

- PR-AUC: 0.9992
- 5-fold CV PR-AUC: 0.9994 ± 0.0002
- F1 (optimal threshold): 0.9372
- Business cost (FN=40k, FP=500): ₹17,500
- Recall: 100%
- Precision: 88.18%
- Optimal threshold: 0.02

> ℹ️ Note: The near‑perfect metrics suggest the dataset is synthetic or strongly separable. Confirmed by 5-fold CV (0.9994 ± 0.0002) — the score is stable and not a lucky split. All anti‑leakage measures were strictly followed, including a single-feature PR-AUC diagnostic (max 0.51) confirming no individual feature drives the result.

## Key dependencies

See `requirements.txt`
