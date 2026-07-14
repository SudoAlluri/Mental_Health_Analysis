
# Project: Mental Health Risk Prediction

This project uses a mental health dataset to explore which personal and lifestyle factors are associated with an individual's mental health risk level. The repository includes dataset files, visualization workbooks, and predictive code for estimating `mental_health_risk` from unseen input data.

## Objective

- Analyze relationships between features such as `age`, `gender`, `employment_status`, `work_environment`, `mental_health_history`, `seeks_treatment`, `stress_level`, `sleep_hours`, `physical_activity_days`, `depression_score`, `anxiety_score`, `social_support_score`, `productivity_score`, and `mental_health_risk`.
- Develop a prediction model that estimates `mental_health_risk` for new, unseen records.

## Key findings (summary)

- Visualizations and correlation analysis investigate whether these features are associated with the risk level.
- The notebooks explore how stress level, sleep hours, depression score, anxiety score, social support, and productivity relate to `mental_health_risk`.
- The model code demonstrates a proof-of-concept risk prediction workflow. Current results indicate the dataset is useful for identifying risk-related patterns, but further feature engineering and validation are needed for a production-ready predictor.

## Files of interest

- `mental_health_dataset.csv`, `mental_health_dataset.xlsx` — raw data
- `CrimeNN-checkpoint.ipynb`, `ml_hw3.ipynb`, `Grad_Ml_project.ipynb` — notebooks with EDA, preprocessing, correlation analysis, experimental details, and plots
- `NeuralNetwork.py` — simple model script used for experiments
- `CORRELATION ANALYSIS.pdf`, `ML_hw3.pdf` — exported summaries and reports
- `visualization.twb`, `visualization_ml.twb`, `~visualization__*.twbr` — Tableau visualizations

## Reproducing the experiments

1. Create and activate a Python virtual environment (Python 3.9+ recommended):

```powershell
python -m venv venv
venv\Scripts\activate
```

2. Install dependencies (or create a `requirements.txt` if you prefer exact versions):

```powershell
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras jupyter
```

3. Run the notebooks in Jupyter to reproduce EDA and plots, and run `NeuralNetwork.py` for the model experiments.

## Next steps (recommended)

- Create a `requirements.txt` with pinned versions.
- Extract and summarize the key numerical results (accuracies, confusion matrices, correlation coefficients) into the README or a short `RESULTS.md`.
- Improve feature engineering (e.g., district-level encoding, temporal features), address class imbalance, and rerun model experiments.

---

If you want, I can extract specific numeric findings (accuracies, correlation coefficients) from the notebooks and update the “Key findings” section with exact numbers. Tell me which notebooks to prioritize.


