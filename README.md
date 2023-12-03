# Customer Churn Survival Analysis

## Project Files

- `Marketing_HW3.ipynb`: Jupyter notebook with Python code for survival analysis.
- `telco.csv`: Dataset for the analysis, containing customer data and churn information.
- `requirements.txt`: Lists Python packages required for running the notebook.

## Project Overview

The assignment involves predicting customer churn through survival analysis. The notebook `Marketing_HW3.ipynb` demonstrates data loading, model fitting (Weibull, LogNormal, LogLogistic, Exponential), model comparison, and survival curve plotting.

## Setup and Installation

Follow these steps to set up the project environment:

1. **Clone the Repository**: Clone this repository to your local machine.
2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```
3. **Activate the Virtual Environment**:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
6. **Run the Notebook**: Open `Marketing_HW3.ipynb` and execute the cells.

## Analysis Results

The notebook's analysis suggests the LogNormal model as the most suitable, based on AIC and BIC scores. The survival curves of all models are visually compared within the notebook.
