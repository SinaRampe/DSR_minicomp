# DSR 29 mini-competition

## 1. Description

This mini competition is adapted from the [Kaggle Rossmann challenge](https://www.kaggle.com/c/rossmann-store-sales/overview).



**Goal**: Predict Sales of a given Rossmann store on a given day.

**Input**: train.csv and store.csv file. A description for the information contained in those files can be found on [Kaggle](https://www.kaggle.com/c/rossmann-store-sales/data ).

**Output**: submission.csv file from the holdout.csv file with two columns: (store) ID and Sales Prediction.

###Team members
Sina Rampe

Oskar Klaja

Aloïs Villa

## 2. Setup
1. From your terminal, clone the repository:

With SSH: `git clone git@github.com:alovg/DSR_minicomp.git`

With HTTPS: `git clone https://github.com/alovg/DSR_minicomp.git`

2. Compatible python version is 3.8.12

If you have jupyter notebook installed in your 'base' environment run:
`conda create -n minicomp python=3.8.12 pip ipykernel`

Otherwise: install jupyter notebook in miniconda environment with `pip3 install jupyter`


3. Get requirements by running `pip3 install -r requirements.txt`
4. Run file

    1. from the cloned repository in your terminal, run `jupyter notebook`
    2. navigate to _xgb_group1.ipynb_ in browser 
    3. Run all cells (from taskbar: go to run> run all cells)

6. You should now have a submission.csv file in the same folder.

## 3. Folder structure

Once cloned, the structure of the folder should look like:

DSR_minicomp

├── data

├── team-work

├── .gitignore

├── README.md

└── Requirements.txt`


The data folder should look like:

data

├── holdout_b29.csv

├── store.csv

└── train.csv

## 4. Model description
###Features

### Model

### Scoring


