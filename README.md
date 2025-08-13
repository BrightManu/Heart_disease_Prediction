# Heart Disease Prediction

A compact, end-to-end ML workflow to predict heart disease from clinical features.  
The notebook covers exploratory analysis, preprocessing, model training, and evaluation.

## Repository
- `HD_Data_exploration_preprocessing.ipynb` — single notebook with:
  - Data loading & schema checks
  - EDA (distributions, correlations, target balance)
  - Preprocessing (imputation, encoding, scaling)
  - Train/validation split (stratified)
  - Model training (classification) and metric reporting
  - Basic visualizations

## Quickstart
```bash
# clone
git clone https://github.com/BrightManu/Heart_disease_Prediction.git
cd Heart_disease_Prediction

# install dependencies
pip install -U pandas numpy scikit-learn matplotlib seaborn jupyter

# run
jupyter notebook HD_Data_exploration_preprocessing.ipynb
