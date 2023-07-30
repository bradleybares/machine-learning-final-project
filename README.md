# Machine Learning & Pattern Recognition Final Project

This final project is a part of the Machine Learning & Pattern Recognition course (EECE5644) at Northeastern University. The project is about the analysis of the [2023 Boston Property Assessment](https://data.boston.gov/dataset/property-assessment/resource/1000d81c-5bb5-49e8-a9ab-44cd042f1db2) dataset. The dataset contains 180,000 records of property assessment in Boston. The goal of this project is to predict the value of a property based on its features. The project incorporates data preprocessing, feature engineering, and machine learning techniques to achieve the goal. The project report can be found [here](https://github.com/bradleybares/machine-learning-final-project/blob/main/boston_property_analysis_report.pdf). The best performing model was a LinearSVR model with a R2 Score of .7113 (30% of the cleaned dataset was heldout for testing).

## Requirements

### Python >= 3.10.2

Most systems will have Python installed, to verify your version run `python3 --version` in your command line. If your version is lower than 3.8 or the command does not return a version number, visit the Python [downloads page](https://www.python.org/downloads/) and download the latest version.

Alternatively you can use a python environment manager such as [pyenv](https://github.com/pyenv/pyenv) to install and manage your python versions. This is the recommended method as it allows you to easily switch between python versions depending on the project.

### Poetry

Poetry is a python package manager and virtual environment manager. It is used to install the required dependencies and manage the project's virtual environment. To install poetry visit the [Poetry installation page](https://python-poetry.org/docs/#installation) and follow the instructions for your operating system.

## Installation

Clone the repository using your preferred cloning method or download the ZIP.

Navigate to the project directory and run `poetry install` in your command line. This will install all the required dependencies and create a virtual environment for the project. To activate the virtual environment run `poetry shell` in your command line.

## Usage

Run each of the notebooks in the `src` directory independently. The data cleaning notebook must be first as it creates the cleaned dataset that is used in the other notebooks. The notebooks can be run in any order after the data cleaning notebook.

## Project Status

The project is complete and no further development is planned.