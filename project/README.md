# DSCI521 Data Analysis and Interpretation: Classifying Major Fire Incidents and Predicting Fire Incident Locations


# Pre-Requisites
In order to install the packages required, you will first need to complete the following pre-requisites if not done:
- Install Python 3.9 or greater for you OS (ex. Windows, MacOS, Linux). The version of python can be done with the following command:
```bash
python --version
```
- Install Pip 22.1 or greater for you OS (ex. Windows, MacOS, Linux) The version of python can be done with the following command:
```bash
pip --version
```

## Python Libraries
Next step is to install the libraries that are used by running the following:
```bash
pip install -r requirements.txt
```

# Jupyter Notebook Execution
1. Open the notebook [here](phase-2/Phase_2_Code.ipynb)
2. Select **Clear All Outputs**
3. Select **Run All**
4. Visualize output under cells for execution
5. View csv output for the following:
    - [Classifying Major Fire Incident - Training Data](phase-2/train-major-fire-incident-classifier-results.csv)
    - [Classifying Major Fire Incident - Testing Data](phase-2/test-major-fire-incident-classifier-results.csv)
    - [Predicting Fire Location - Training Data](phase-2/train-fire-incident-location-classifier-results.csv)
    - [Predicting Fire Location - Testing Data](phase-2/test-fire-incident-location-classifier-results.csv)


# Project
The purpose of this project will be to analyze California wildfire data to learn about the frequency, duration, and amount of damage that a fire can cause to structures and human life. Wildfires in California have been on the rise, especially in recent years, and have caused destruction and devastation in its wake. Analyzing this wildfire data will can give us an insight into potential patterns that may exist and perpetuate in the future.

Our goal is to perform exploratory data analysis and eventually determine the best machine learning model that will enable us to accurately determine if a fire incident is major or not and to best predict the location based on county, where a fire will occur. For both methods, we will hand select features that will enable us to help with classification.

# California Wildfires Data Set
[California Fire Incidents](data/California_Fire_Incidents.csv)

## Images
[Images](images/)

## Phase 1: Exploratory Data Analysis
- [Code](phase-1/Phase_1_Code.ipynb)
- [Report](phase-1/Phase_1_Report.ipynb)

## Phase 2: Machine Learning
- [Code](phase-2/Phase_2_Code.ipynb)
- [Report](phase-2/Final_Report.ipynb)

# Authors
- [Austin Eversole](ae588@drexel.edu)
- [Greg Savage](gs824@drexel.edu)
- [Robert Thompson](rt598@drexel.edu)
