# Beauty & Wellness: Reducing Product Mismatch in Online Skincare

Data science internship project (Week 1: Orientation & Problem Definition).

## Problem statement
Online skincare shoppers often buy products that do not suit their skin type, concerns or sensitivities. This leads to returns, negative reviews and lower repeat purchases. This project explores how customer attributes, product ingredients and review sentiment can power personalized recommendations that reduce mismatch.

## Objectives
1. Identify drivers of dissatisfaction and returns in online skincare.
2. Extract aspect-level signals (efficacy, irritation, texture, scent, value) from review text.
3. Build a hybrid, profile-aware recommender.
4. Compare it against a popularity-based baseline.
5. Turn findings into recommendations for merchandising and marketing.

## Research questions
- RQ1: Which product, ingredient and customer attributes are linked to negative sentiment?
- RQ2: Do different skin types describe the same product differently?
- RQ3: Do aspect-level sentiment features improve satisfaction prediction over star ratings alone?
- RQ4: Does a hybrid recommender beat a popularity baseline?
- RQ5: How does a poor first experience affect repeat purchase?

## Planned approach
1. Business understanding
2. Data collection (open datasets, e.g. Kaggle / UCI / public review corpora)
3. Cleaning and preparation
4. Exploratory data analysis
5. Feature engineering (sentiment aspects, ingredient flags, RFM)
6. Segmentation and hypothesis testing
7. Modelling (satisfaction prediction, recommenders)
8. Evaluation (precision@k, NDCG, ROC-AUC, cross-validation)
9. Interpretation
10. Recommendations and dashboard

## Tech stack
Python, pandas, NumPy, scikit-learn, NLTK/spaCy, VADER, Hugging Face Transformers, XGBoost/LightGBM, Matplotlib/Seaborn/Plotly, Jupyter.

## Repository structure
```
docs/        Week 1 problem definition report (.docx)
data/raw/    Original datasets (not committed if large or licensed)
data/processed/  Cleaned data
notebooks/   EDA and modelling notebooks
src/         Reusable code
reports/     Figures and later reports
```

## Setup
```bash
pip install -r requirements.txt
jupyter notebook
```

## Status
- [x] Week 1: Problem definition and plan (see `docs/`)
- [ ] Data collection and cleaning
- [ ] EDA and text analytics
- [ ] Modelling and evaluation
- [ ] Final insights

## Notes
Data is used for analysis only. This project does not provide medical advice.
