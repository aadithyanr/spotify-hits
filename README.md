# Predicting Whether a Song Will Be a Billboard Hit

Artificial Intelligence Final Project

**Researchers:** Aadithyan Nair, Ananya Trivedi, Dhruv Vaswani

**Faculty guide:** Dr. Pallavi Dhade

## The Project

This project uses audio features, lyrical features, and artist information to predict whether a song will become a Billboard Top 100 hit. We evaluate Logistic Regression, Support Vector Machine, Neural Network, Gradient Boosting, Random Forest, and XGBoost classifiers.

## Installation

```bash
git clone https://github.com/aadithyanr/spotify-hits.git
cd spotify-hits
pip3 install -r requirements.txt
```

If Spotify API access is required, create a local `config.cfg` in the repository root and add your own credentials.

## Running the Project

Run `Modeling.ipynb` and `Modelling.ipynb` to reproduce the models discussed in the report. The prepared datasets are included in `data/`. To recreate the training subset, run `CreateFinalSubset.ipynb`.

## Repository Contents

- `303_Final_Report_2.pdf` - Final research paper
- `CreateFinalSubset.ipynb` - Creates the training subset from the final dataset
- `Modeling.ipynb` - Logistic Regression, Neural Network, Gradient Boosting, and XGBoost models
- `Modelling.ipynb` - Random Forest, SVM, and an additional Gradient Boosting model
- `data/` - Prepared datasets and model output
- `archived/` - Earlier exploratory notebooks
- `requirements.txt` - Python dependencies
