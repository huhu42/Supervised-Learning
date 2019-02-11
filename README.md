# Assignment 1 - Supervised Learning - Liyue (Nikki) Hu

This package should contain all code and data necessary to run all of the expierments for assignment 1.

Credit to cmaron ([https://github.com/cmaron](https://github.com/cmaron)) for sharing his code.

## Dataset

This assignment uses two datasets, which can be downloaded:

Credit Card Default: ([https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset ])(https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset)
Pen Digits Recognition: ([https://archive.ics.uci.edu/ml/datasets/Pen-Based+Recognition+of+Handwritten+Digits]) (https://archive.ics.uci.edu/ml/datasets/Pen-Based+Recognition+of+Handwritten+Digits)

## Installation

1. Requirements are outlined in requirements.txt, this project uses Python 3.

If a python virtual environment has been setup for the project, a simple `pip install -r requirements.txt` should take care of the required packages.

```

2. You're set, read the next sections in order to be able to run any of the experiments.  

## Run

```
python run_experiment.py -h

usage: run_experiment.py [-h] [--threads THREADS] [--seed SEED] [--ann]
                         [--boosting] [--dt] [--knn] [--svm] [--all]
                         [--verbose]

Perform some SL experiments

optional arguments:
  -h, --help         show this help message and exit
  --threads THREADS  Number of threads (defaults to 1, -1 for auto)
  --seed SEED        A random seed to set, if desired
  --ann              Run the ANN experiment
  --boosting         Run the Boosting experiment
  --dt               Run the Decision Tree experiment
  --knn              Run the KNN experiment
  --svm              Run the SVM experiment
  --all              Run all experiments
  --verbose          If true, provide verbose output

```


## Example

To run for example, ANN, use the following command.

```
python run_experiment.py -ann
```