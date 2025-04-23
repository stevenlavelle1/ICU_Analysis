# Intensive Care Units: Impact on Irish healthcare services

This project explores an ICU dataset to build predictive models for a variety of healthcare metrics using regression techniques and time series forecasting. This investigation is done using Jupyter Notebooks.

### 🔬 Main Notebooks

- **`FYP.ipynb`**  
  The initial jupyter notebook created for my final year project. It includes data understanding, exploratory data analysis (EDA), preprocessing, feature engineering, to model evaluation and visualization.

- **`timeseries.ipynb` & `timeseries2.ipynb`**  
  These notebooks apply time series forecasting techniques to predict amount of ICU patients entering ICUs focusing on 2 models, one which makes conservative predictions and one that makes bolder predictions. Auto ARIMA and Decision tree models are used.

- **`time_regressions.ipynb`**  
  Creates a regression model to predict the amount of patients entering ICU using previous years admission dates

- **`LOS_regressions.ipynb`**  
  Focused on predicting ICU patients’ **Length of Stay (LOS)** comparing various regression models based on features in the dataset.

- **`diagnosis.ipynb`**  
  Explores classification models to predict possible diagnoses or categorize patients into risk groups.

### Saved Models

- Important trained models have been serialized and saved using 'pickle`.
- ts_AA_model.pkl
- ts_dt_model.pkl
- los_lr_model.pkl
- los_dt5_model.pkl
- los_dt3_model.pkl
- diagnosis_et_model.pkl

## Tools Used

- Python
- Jupyter Notebooks
- Pandas, NumPy
- Matplotlib, Seaborn