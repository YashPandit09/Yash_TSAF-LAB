# Time Series and Forecasting (TSAF) Lab

Welcome to the **Time Series and Forecasting (TSAF)** repository. This project contains Python Jupyter Notebooks and datasets focusing on time-series analysis, datetime manipulations, date range generation, missing value interpolation, and real-world dataset analysis.

---

## 📁 Repository Structure

```text
.
├── 1_datetime.ipynb            # Python standard datetime module basics
├── 2_pandas_datetime.ipynb     # Advanced Pandas datetime operations & UPI transaction analysis
├── 3_date_range.ipynb          # Custom date range generation across various frequencies
├── Exp-3.ipynb                 # Medical appointment time-series experiment & lag analysis
├── interpolation.ipynb         # Time-series missing value handling using interpolation
├── data/                       # Directory containing experiment datasets
│   ├── appointsments_data.csv  # Medical appointments dataset
│   ├── traffic_sensor_data.csv # Traffic sensor metrics dataset
│   ├── upi_transactions.csv    # Financial UPI transaction logs
│   └── README.md               # Dataset documentation
└── README.md                   # Main repository documentation
```

---

## 🚀 Notebook Descriptions

| Notebook | Topic / Description | Key Libraries & Functions |
| :--- | :--- | :--- |
| **`1_datetime.ipynb`** | Core Python `datetime` module concepts, `strftime`, `strptime`, timestamp formatting, and `timedelta` calculations. | `datetime` |
| **`2_pandas_datetime.ipynb`** | Pandas datetime indexing, parsing string dates, time delta computations, and analyzing UPI transaction timestamps. | `pandas`, `numpy` |
| **`3_date_range.ipynb`** | Generating time sequences with `pd.date_range()` across custom frequencies (Daily, Business Days, Weekly, Monthly, Hourly, 15-minute intervals). | `pandas`, `numpy` |
| **`Exp-3.ipynb`** | Time series analysis on medical appointments (`data/appointsments_data.csv`). Calculates scheduling-to-appointment lead times and date feature extraction. | `pandas` |
| **`interpolation.ipynb`** | Handling missing data in time series using forward/backward and linear interpolation (`df.interpolate()`). | `pandas`, `numpy` |

---

## 📊 Datasets (`data/`)

All datasets are stored in the [`data/`](data/) directory:

1. **`data/appointsments_data.csv`**: Contains appointment IDs, patient demographics, scheduled dates, appointment dates, and attendance flags.
2. **`data/traffic_sensor_data.csv`**: Contains high-frequency traffic volume and sensor telemetry for time series modeling.
3. **`data/upi_transactions.csv`**: Contains digital payment records, timestamps, transaction amounts, and category labels.

---

## 🛠️ Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed along with Jupyter and the necessary data science libraries:

```bash
pip install pandas numpy jupyter matplotlib
```

### Running the Notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/YashPandit09/Yash_TSAF-LAB.git
   cd Yash_TSAF-LAB
   ```

2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open any of the `.ipynb` files to execute the experiments.
