# Predictive-Maintenance-System-using-Machine-Learning-XGBoost-.
This project is a Predictive Maintenance System using Machine Learning (XGBoost). It predicts whether a machine is likely to fail based on sensor and operating data.
# Predictive Maintenance using XGBoost

A Machine Learning project that predicts machine failures using sensor and operational data.

This project uses the XGBoost Classifier to build a predictive maintenance system for industrial machines.

---

## Features

- Predicts machine failure before breakdown
- Uses Machine Learning for classification
- Data preprocessing and feature engineering
- High accuracy using XGBoost
- Model saving using Joblib

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib

---

## Dataset Features

| Feature | Description |
|---|---|
| Type | Machine quality type |
| Air temperature | Ambient temperature |
| Process temperature | Machine process temperature |
| Rotational speed | RPM of machine |
| Torque | Rotational force |
| Tool wear | Tool usage duration |
| Target | Failure prediction |

---

## Project Workflow

```text
Load Dataset
   ↓
Data Cleaning
   ↓
Feature Encoding
   ↓
Train-Test Split
   ↓
Train XGBoost Model
   ↓
Prediction
   ↓
Accuracy Evaluation
   ↓
Save Model
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/predictive-maintenance-xgboost.git
```

Move into project folder:

```bash
cd predictive-maintenance-xgboost
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python main.py
```

---

## Model Training

```python
XGBClassifier(
    n_estimators=200,
    learning_rate=0.05,
    max_depth=5
)
```

---

## Accuracy

Example Output:

```text
Train Accuracy: 0.99
Test Accuracy: 0.98
```

---

## Save Model

The trained model is saved as:

```text
xgboost_predictive_maintenance.pkl
```

---

## Applications

- Smart Manufacturing
- Industrial Automation
- Aircraft Maintenance
- Railway Monitoring
- Automobile Industry
- Power Plants

---

## Future Improvements

- Deploy using Flask or Streamlit
- Real-time sensor integration
- Dashboard visualization
- Deep Learning implementation

---

## Author

Yash Kamde

---

## License

This project is open-source and available under the MIT License.
