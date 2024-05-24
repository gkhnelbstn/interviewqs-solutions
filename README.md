# 🧠 InterviewQs Daily Challenge Solutions

Welcome to my InterviewQs challenges data science repository! This repository is created to help you solving problems in InterviewQs' daily challenges, in a well-structured and organized project setup.

## 🌟 Project Overview

Project Overview
This project focuses on tackling InterviewQs' daily coding challenges. We'll be working with various datasets related to these challenges and aiming to develop solutions that effectively address the problems presented.

## 🔧 Requirements

To use this project, make sure you have the following installed:

- **Python**: 2.7 or 3.5+
- **Libraries**: Pandas, Numpy, itertools

## 📁 Directory Structure
Information about project folder structure:

## 📦 project_name
- [LICENSE](./LICENSE)
- [Makefile](./Makefile) - Makefile with commands like `make data` or `make train`
- [README.md](./README.md) - The top-level README for developers using this project.
- [data](./data)
  - [external](./data/external) - Data from third party sources.
  - [interim](./data/interim) - Intermediate data that has been transformed.
  - [processed](./data/processed) - The final, canonical data sets for modeling.
  - [raw](./data/raw) - The original, immutable data dump.
- [docs](./docs) - A default Sphinx project; see [sphinx-doc.org](https://www.sphinx-doc.org/) for details.
- [models](./models) - Trained and serialized models, model predictions, or model summaries.
- [notebooks](./notebooks) - Jupyter notebooks. Naming convention is a number (for ordering), the creator's initials, and a short `-` delimited description, e.g. `1.0-jqp-initial-data-exploration`.
- [references](./references) - Data dictionaries, manuals, and all other explanatory materials.
- [reports](./reports) - Generated analysis as HTML, PDF, LaTeX, etc.
  - [figures](./reports/figures) - Generated graphics and figures to be used in reporting.
- [requirements.txt](./requirements.txt) - The requirements file for reproducing the analysis environment, e.g. generated with `pip freeze > requirements.txt`.
- [setup.py](./setup.py) - Makes project pip installable (`pip install -e .`) so `src` can be imported.
- [src](./src) - Source code for use in this project.
  - [__init__.py](./src/__init__.py) - Makes `src` a Python module.
  - [data](./src/data) - Scripts to download or generate data.
    - [make_dataset.py](./src/data/make_dataset.py)
  - [features](./src/features) - Scripts to turn raw data into features for modeling.
    - [build_features.py](./src/features/build_features.py)
  - [models](./src/models) - Scripts to train models and then use trained models to make predictions.
    - [predict_model.py](./src/models/predict_model.py)
    - [train_model.py](./src/models/train_model.py)
  - [visualization](./src/visualization) - Scripts to create exploratory and results-oriented visualizations.
    - [visualize.py](./src/visualization/visualize.py)
- [tox.ini](./tox.ini) - tox file with settings for running tox; see [tox.readthedocs.io](https://tox.readthedocs.io/).


## 🛠️ Installing Development Requirements
To install the development requirements, run:
```
pip install -r requirements.txt
```
## ✅ Running the Tests
To run the tests, use:
```
py.test tests
```
Happy coding! 🎉 If you have any questions, feel free to reach out to [gkhnelbstn](https://github.com/gkhnelbstn).

Feel free to adjust the content as needed and enjoy your data science projects!

