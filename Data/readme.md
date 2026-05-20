# Data

The datasets used in this project were provided by the ChurnZero 26 competition via the Unstop platform.

## Files (not committed — competition rules)

- `ChurnZero_dataset_v1.csv` — 8,101 rows, 97 features + target (`churn`)
- `ChurnZero_test_v1.csv` — 2,026 rows, 97 features, no target

## To reproduce

Place both CSV files in this folder, then run from the root:

```bash
python churnzero_code.py
```

The script will read from `data/` automatically.
