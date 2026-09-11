![Python](https://img.shields.io/badge/python-3.11%2B-success)
[![License: BSD](https://img.shields.io/badge/license-BSD-success.svg)](https://github.com/solegalli/machine-learning-interpretability/blob/main/LICENSE)
[![Powered by Train in Data](https://img.shields.io/badge/Powered%20By-TrainInData-orange.svg)](https://www.trainindata.com/)

# Machine Learning Interpretability

Learn how to interpret and explain machine-learning models — from intrinsically interpretable models like linear regression and decision trees, to post-hoc methods like permutation importance, partial dependence, ALE, LIME and SHAP.

This repository contains the practical notebooks for the **[Machine Learning Interpretability](https://www.trainindata.com/p/machine-learning-interpretability)** course. The examples cover both intrinsically explainable models and model-agnostic post-hoc explainability methods, using scikit-learn, statsmodels, XGBoost, LightGBM, eli5, LIME, and SHAP.

**Course launch:** November 2023

**Last updated:** September 2026

**Status:** Actively maintained

[<img src="./mli_logo.png" width="248" alt="Train in Data">](https://www.trainindata.com/p/machine-learning-interpretability)

## What you will learn

- Tell apart local vs. global, and intrinsic vs. post-hoc interpretability.
- Interpret linear and logistic regression, decision trees, random forests, and gradient boosting machines natively.
- Quantify global feature importance with permutation importance, partial dependence plots, and accumulated local effects (ALE).
- Explain individual predictions with individual conditional expectation (ICE) plots, surrogate models, LIME, and SHAP.
- Compare exact and approximate Shapley value calculations, including TreeSHAP, the exact explainer, and the permutation explainer.
- Use eli5, LIME, and SHAP in practice, and understand the assumptions and trade-offs behind each method.

## Course contents

1. **Machine Learning Interpretability**
   - Interpretability in the context of Machine Learning
   - Local vs Global Interpretability
   - Intrinsically explainable models
   - Post-hoc explainability methods
   - Challenges to interpretability
   - How to make models more explainable

2. **Intrinsically Explainable Models**
   - [Linear regression](04-linear-regression)
   - [Logistic regression](05-logistic-regression)
   - [Decision trees](06-decision-trees)
   - [Random forests](07-random-forests)
   - [Gradient boosting machines](08-gradient-boosting-machines)

3. **Post-hoc methods - Global explainability**
   - [Permutation feature importance](09-permutation-feature-importance)
   - [Partial dependence plots](10-partial-dependence-plots)
   - [Accumulated local effects (ALE)](11-ale-plots)

4. **Post-hoc methods - Local explainability**
   - [Individual conditional expectation (ICE)](12-ice-plots)
   - [Surrogate models](13-surrogates)
   - [LIME](14-lime)
   - [SHAP](15-shap)

5. **Featuring the following Python interpretability libraries**
   - scikit-learn
   - statsmodels
   - eli5
   - LIME
   - SHAP

## Getting started

Clone the repository and set up a dedicated Python environment (Python 3.11+).

Take a look at [requirements.txt](requirements.txt) and install what you need for the sections you plan to work through. `keras` and `tensorflow` are listed separately as optional — they're only needed for the LIME text and image notebooks in [14-lime](14-lime), so there's no need to install them if you're not running those.

Then start Jupyter and open the notebooks in numerical order.

## Course

For lectures, explanations, and the complete learning path, visit the [online course](https://www.trainindata.com/p/machine-learning-interpretability).
