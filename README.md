# EDA Project with Data of the House Market in King County in 2014 and 2015

This Notebook is written in an iterative way. Each section (excluding the import data section) was worked on a couple of times.
It's sectioned into following parts:
<br>
* Importing the data
* Checking the data
* Hypotheses
* Cleaning the data
    * Includes creating a new column (price_per_sqft)
    * Making some plots to determine what is relevant and what not
* Checking hypotheses
    * Each hypothesis gets its own section
    * Each hypothesis gets its own conclusion
* Findings


## Requirements

- pyenv
- python==3.9.8


This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

In order to install the environment you can use the following commands:

```
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
