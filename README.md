
# HR Attrition Analytics & Prediction (Streamlit Cloud)

- `app.py` — main Streamlit app
- `requirements.txt` — minimal list (no versions)

## Deploy
1. Create a GitHub repo.
2. Add `app.py`, `requirements.txt` and optionally your `EA.csv`.
3. In Streamlit Cloud, set the main file to `app.py` and deploy.

## Notes
- Insights tab has 5 actionable charts with global filters (JobRole, Satisfaction range).
- Modeling tab trains DT/RF/GBRT with 5-fold stratified CV, shows confusion matrices (train/test), a single ROC curve, metrics, and feature importances.
- Upload & Predict tab trains the chosen model on the full dataset and predicts on a new CSV, with a download button for results.
