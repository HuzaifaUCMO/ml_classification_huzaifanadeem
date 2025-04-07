# Titanic Survival Classification  
**Author:** Huzaifa Nadeem | **Date:** 4-6-2025

---

## Overview
This project predicts whether a passenger survived the Titanic disaster using machine‑learning classifiers.  
I explore Kaggle’s `train.csv`, clean and engineer features, then compare three models—Decision Tree, Logistic Regression, and Random Forest.  
Random Forest delivers the best accuracy.
My notebook file https://github.com/HuzaifaUCMO/ml_classification_huzaifanadeem/blob/main/classification_huzaifanadeem.ipynb
My peer review https://github.com/HuzaifaUCMO/ml_classification_huzaifanadeem/blob/main/peereview.md
---

## Files
| Path | Purpose |
|------|---------|
| `data/train.csv` | Raw Titanic dataset (downloaded from Kaggle) |
| `classification_huzaifanadeem.ipynb` | Fully executed notebook with code, plots, and reflections |
| `images/` | Saved confusion matrix / EDA plots (optional) |
| `peer_review.md` | My review of a classmate’s project |
| `README.md` | This file |

---

## Quick Start

```bash
# clone repo
git clone https://github.com/HuzaifaUCMO/ml_classification_huzaifanadeem.git
cd ml_classification_huzaifanadeem

# (optional) create virtual env
python -m venv .venv
source .venv/Scripts/activate   # Windows
# source .venv/bin/activate     # macOS / Linux
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# launch notebook
jupyter notebook
# open classification_huzaifanadeem.ipynb and Run All


Method (short)
Clean – filled missing Age, imputed Embarked, dropped sparse Cabin, Ticket, Name.

Engineer – added FamilySize and IsAlone; encoded Sex, Embarked.

Models – trained Decision Tree, Logistic Regression, Random Forest.

Metrics – evaluated on Accuracy, Precision, Recall, F1, confusion matrix.

Results
Random Forest achieved the highest F1 (≈ 0.79) and accuracy (≈ 0.84), outperforming the single‑tree and linear baselines.