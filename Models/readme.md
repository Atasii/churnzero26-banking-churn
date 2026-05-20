# Models

Trained model artefacts are generated automatically when you run the main script.

## Files (not committed — regenerated from code)

- `xgb_churn_model.pkl` — trained XGBoost model
- `scaler.pkl` — fitted StandardScaler
- `encoders.pkl` — fitted LabelEncoders for categorical columns
- `feature_cols.pkl` — ordered feature list used during training
- `threshold.txt` — optimal decision threshold (business cost-tuned)

## To regenerate

```bash
python churnzero_code.py
```

All artefacts will be saved here automatically after training completes.
