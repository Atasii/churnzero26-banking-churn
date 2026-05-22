# ChurnZero26 – Banking Customer Churn Prediction

## Team: atasikolexi05

## Reproducing the model

1. Install requirements: `pip install -r requirements.txt`
2. Place dataset CSVs in `Data/` folder.
3. Run `Models/churnzero_atasikole_code.ipynb` (run all cells).
4. Predictions output: `Predictions/ChurnZero_Atasikole_Predictions.csv`

## Validation performance

- PR-AUC: 0.7234
- F1 (optimal threshold): 0.5841
- Business cost (FN=40k, FP=500): 142500

## Key dependencies

See `requirements.txt`
