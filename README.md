# Prediction and Assessment of Green Ammonia Production in India

This repository contains the code and data from my research internship at IIT Roorkee, focused on predicting and assessing the potential for green ammonia production using solar energy and advanced machine learning models.

Project Structure
notebooks/: Jupyter notebooks for data processing, modeling, and analysis.

data/: All CSV datasets required for running the notebooks.

requirements.txt: List of Python dependencies for reproducibility.

Notebooks Overview
1.5Mw_power.ipynb: Power prediction for a 1.5MW solar plant using meteorological data.

Ammonia.ipynb: End-to-end prediction pipeline for solar power, hydrogen, and ammonia production.

power_with_hydrogen.ipynb: Focused on hydrogen production modeling from solar power.

powerprediciton50Kw.ipynb: Power prediction for a 50kW solar setup.

total_production.ipynb: Calculates annual total production of power, hydrogen, and ammonia.

Data Files
1.5MWfinal1.csv: Dataset for 1.5MW plant predictions.

solar_data_new.csv: General solar power dataset.

solar_data_new_Ammonia.csv: Dataset for ammonia production modeling.

solar_data_new_hydrogen.csv: Dataset for hydrogen production modeling.

All data files are in the data/ directory. Each notebook specifies which CSV it uses.

How to Run
Clone this repository.

Install dependencies:

text
pip install -r requirements.txt
or
pandas==2.2.2
numpy==1.26.4
scikit-learn==1.5.0
matplotlib==3.9.0
tensorflow==2.16.1
jupyter==1.0.0

Open the desired notebook in Jupyter and run the cells.

Acknowledgements
This work was completed as part of a research internship at the Indian Institute of Technology, Roorkee, Department of Hydro and Renewable Energy.
