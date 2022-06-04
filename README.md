# EDA project

First EDA project in the neuefische Data Science course. The topic is real state analysis in King County, Washington, USA, for a certain stakeholder

Consists of two notebook:
- EDA_project_1 with the general analysis of the data set
- EDA_project_2 with the special research focus for the stakeholder

## Requirements

- pyenv
- python==3.9.8
- package information in the requirements file, run with pip

## Setup

General workflow to set up your virtual environment:

* setting the python version locally to 3.9.8
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

Commands to set up the venv and install the python package:

- pyenv local 3.9.8
- python -m venv .venv
- source .venv/bin/activate
- pip install --upgrade pip
- pip install -r requirements.txt