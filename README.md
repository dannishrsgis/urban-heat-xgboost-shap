# urban-heat-xgboost-shap
XGBoost-based Land Surface Temperature (LST) modeling and SHAP-based interpretability for urban heat analysis
# Urban Heat Modeling using XGBoost and SHAP

This project models Land Surface Temperature (LST) across Delhi using the XGBoost machine learning algorithm, and interprets the results using SHAP (SHapley Additive Explanations). The study identifies the influence of socio-economic, built-up, terrain, and green-blue landscape factors on urban heat dynamics.

## 📂 Repository Structure

- `shap_analysis.py`: Main script for model training and SHAP visualization.
- `data/`: Example or reference datasets (if included).
- `figures/`: Resulting plots and interpretability maps.
- `requirements.txt`: Python packages used.

## 📊 Features Analyzed

- Population Density (POPD)
- Nighttime Light (NTL)
- Building & Road Density (BD, RD)
- Impervious Surface (ISP)
- Vegetation & Water metrics (PLAND, PD, COHESION, etc.)

## 🧠 Tools Used

- Python (XGBoost, SHAP, Scikit-Learn)
- Plotly, Matplotlib, Pandas
