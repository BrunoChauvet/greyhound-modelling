# Betfair Greyhound Modelling

## Project Setup

This project assume you have a developmemnt environment with [Python](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installation/) installed

Clone project
```
git clone git@github.com:betfair-down-under/autoHubTutorials.git
```

Install python libraries
```
cd greyhound-modelling
pip install --user -r requirements.txt
```

Create a configuration file named `.env` in the rot folder and set required values:
```
FAST_TRACK_API_KEY=<your key>
```

Launch notebook
```
jupyter notebook
```

## Notebooks

Below is the list of notebooks with detailed examples

### Classification Models

[greyhound_racing_modelling](notebook/greyhound_racing_modelling.ipynb) provides a step-by-step tutorial from fetching Greyhound racing data from FastTrack API to generating win probabilities using [Scikit-learn](https://scikit-learn.org/stable/) and various Classification techniques.

### Models Ensemble

TODO

### Model Backtesting

TODO
