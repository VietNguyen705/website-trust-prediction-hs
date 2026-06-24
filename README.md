# Predicting User Trust and Aesthetic Perception from Website Design

A 10-week summer research project for high school students.

Title: Predicting User Trust and Aesthetic Perception from Website Design Using Machine Learning.

Research question: Can machine learning predict user trust, aesthetics, and usability ratings from visual website design features?

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VietNguyen705/website-trust-prediction-hs/blob/master/website_trust_prediction.ipynb)

## Dataset

Dataset of User Evaluations of Prototypicality, Aesthetics, Usability and Trustworthiness of Homepages (2024), covering banking, e-commerce, and university websites. Each homepage has a screenshot and user ratings.

Reference: https://www.unboundmedicine.com/medline/citation/38287953/

## How to start

1. Open `website_trust_prediction.ipynb` (in Jupyter or Google Colab).
2. If on Colab, switch the runtime to GPU is not required; CPU is fine.
3. Put the ratings file (`homepage_ratings.csv`) and a `screenshots/` folder in your project directory, then fill in every TODO cell from top to bottom.

`website_trust_prediction_solution.ipynb` is the worked solution -- only check it if you are stuck. Ask your instructor if stuck.

## 10-Week Plan

| Week | Tasks |
|---|---|
| 1 | Research background and literature review: HCI, website credibility, first impressions, visual complexity, prototypicality, trust and usability. Read 3-5 papers, summarize, find gaps. No coding |
| 2 | Dataset exploration: load the data, examine the rating variables, homepage categories, and the user evaluation process. Build a variable description table |
| 3 | Exploratory data analysis: rating distributions, compare website categories, and relationships among trust, aesthetics, usability, and prototypicality |
| 4 | Feature extraction from screenshots: color (colorfulness, contrast), layout (whitespace, density), and complexity (edge density, entropy). Build the feature dataset |
| 5 | Data visualization and design analysis: visualize design features, compare high vs low trust and high vs low aesthetic pages |
| 6 | Baseline models: train/test split, then Linear, Ridge, and Decision Tree regression to predict trust, aesthetics, and usability |
| 7 | Advanced models: Random Forest and Gradient Boosting with cross-validation and hyperparameter tuning. Performance comparison table |
| 8 | Explainable AI: feature importance, SHAP values, partial dependence. Which design features most influence perceived trust? |
| 9 | Interaction analysis: complexity x prototypicality, colorfulness x trust, symmetry x usability. Test hypotheses from the literature |
| 10 | Write the paper (intro, related work, dataset, methods, results, discussion, future work, references) and present |

## Files

- `website_trust_prediction.ipynb` - student template (fill in the TODOs)
- `website_trust_prediction_solution.ipynb` - worked solution
- `WebDesginMLHS project.pdf` - the original project brief
