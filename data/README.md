# Datasets Directory (`data/`)

This directory contains the datasets used across the Time Series and Forecasting (TSAF) laboratory experiments.

## Included Datasets

| Dataset File | Description | Primary Use Case |
| :--- | :--- | :--- |
| `appointsments_data.csv` | Medical appointment scheduling and attendance records | Analyzed in `Exp-3.ipynb` for lead-time calculations and attendance prediction. |
| `traffic_sensor_data.csv` | High-frequency traffic sensor telemetry and volume data | Time-series trend analysis, seasonality, and traffic forecasting. |
| `upi_transactions.csv` | Log of UPI payments and digital transaction timestamps | Analyzed in `2_pandas_datetime.ipynb` for datetime indexing and transaction pattern extraction. |

## Path Reference in Code

When loading these datasets in Pandas, use the relative path `data/<filename>`:

```python
import pandas as pd

# Example
df_appointments = pd.read_csv("data/appointsments_data.csv")
df_upi = pd.read_csv("data/upi_transactions.csv")
df_traffic = pd.read_csv("data/traffic_sensor_data.csv")
```
