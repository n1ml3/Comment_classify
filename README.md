# Comment_classify — Toxic Comment Detection 

Short project repository for preprocessing, exploring, and preparing a small toxic-comment / tweet dataset for basic NLP and ML practice. The analysis and preprocessing are implemented in the main notebook `Project.ipynb` and the processed CSV outputs live in the `Data/` folder.

---

## Contents

- `Project.ipynb` — main analysis and preprocessing notebook.
- `Data/` — CSV files used and produced by the notebook:
  - `Data_NLP.csv` — original/raw dataset used for NLP preprocessing.
  - `Data_all.csv` — DataFrame after preprocessing; includes original and preprocessed text columns.
  - `Data_finish.csv` — final CSV with `class` and `tweet_ok` (preprocessed) ready for modeling.
  - `Data_Practice_ML_OK.csv` — small practice dataset referenced in the notebook.
- `Pic/` — visual outputs (plots, screenshots) used in analysis.

---

## Overview

This repository contains a single Jupyter notebook that:
- Loads a tweet/comment dataset.
- Cleans and normalizes text (tokenization, stop-word removal, lemmatization, basic normalization).
- Saves intermediate and final CSV files that can be used for model training or further analysis.

The focus is on preprocessing for toxic-comment classification and providing a small, clean dataset for ML practice.

---

## Requirements

The notebook uses Python 3 and common data / NLP packages. Install the minimal set with:

```powershell
python -m pip install --upgrade pip
python -m pip install pandas numpy nltk scikit-learn matplotlib jupyterlab
```

If you prefer a `requirements.txt`, create one with these packages and run `pip install -r requirements.txt`.

---

## NLTK data

The notebook uses NLTK resources (lemmatizer, stopwords). If you haven't downloaded the required NLTK data, run this in Python once (or execute the corresponding notebook cellNam
