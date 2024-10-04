# Dicoding Collection Dashboard

## Overview
This project focuses on exploring and visualizing data from the **Air Quality Dataset**. It leverages Streamlit to create interactive visualizations that provide insights into air quality metrics, including the concentrations of various pollutants in the air. The goal is to analyze the dataset comprehensively, highlighting trends, patterns, and key metrics related to air pollution.

## Data Source
The data used in this project comes from the following source:

- [Air Quality Dataset](https://github.com/marceloreis/HTI/tree/master/PRSA_Data_20130301-20170228)


## Requirements
To run this project, you need to install the following Python packages:

- Babel==2.11.0
- matplotlib==3.8.4
- numpy==1.26.4
- pandas==2.2.2
- seaborn==0.13.2
- streamlit==1.32.0

You can find the required packages listed in the `requirements.txt` file.

## Installation

### Clone the Repository
First, clone the repository:

git clone https://github.com/UWONGMUMET/Proyek-Streamlit/tree/master

cd Proyek-Streamlit

## Create a virtual environment
python -m venv venv

## Activate the virtual environment
### On Windows
venv\Scripts\activate

## Install Dependencies
### Install the required packages:

pip install -r requirements.txt

## Prepare Data
Ensure that you have the following CSV files in the ./data/ directory:
PRSA_DATA_CLEAN.csv

Adjust the file paths in dashboard.py if necessary.

## Running the Dashboard
### Run the Streamlit application:

streamlit run .\dashboard\dashboard.py