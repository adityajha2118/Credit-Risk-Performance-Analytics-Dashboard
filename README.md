# Credit Risk Performance Analytics Dashboard

## Overview
This project provides a comprehensive analytics pipeline for evaluating credit risk. It includes data preparation, feature engineering, and predictive model training using Python, along with an interactive Tableau dashboard for visual performance analytics.

## Project Structure
- `data/`: Contains the raw and processed datasets (e.g., `loan_applicants_data.csv`).
- `notebooks/`: Jupyter Notebooks containing the data science workflow:
  - `01_data_preparation_and_feature_engineering.ipynb`: Data cleaning and feature engineering.
  - `02_model_training.ipynb`: Training and evaluating machine learning models.
- `dashboard/`: Contains the Tableau dashboard files (`.twbx`) for visualizing credit risk analytics.
- `src/`: Directory for reusable Python source code and modules.
- `images/`: Directory for storing project images and screenshots.

## Requirements & Setup

### Python Environment
To run the Jupyter Notebooks and python scripts, you need to install the project dependencies.

1. Ensure you have Python installed.
2. Open your terminal or command prompt and navigate to the project directory.
3. Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter to view the notebooks:
   ```bash
   jupyter notebook
   ```

### Tableau Dashboard
The visual analytics for this project are provided via a Tableau Dashboard. **Tableau is required** to open and interact with the `.twbx` file.

1. Download and install [Tableau Public](https://public.tableau.com/en-us/s/) (Free) or Tableau Desktop.
2. Navigate to the `dashboard/` folder in this repository.
3. Open `Credit_Risk_Performance_Analytics_Dashboard.twbx` using Tableau.
4. Explore the interactive visualizations to analyze credit risk performance.

## Usage
1. **Data Prep:** Run the `01_data_preparation_and_feature_engineering.ipynb` notebook to clean the raw data and generate the processed dataset.
2. **Model Training:** Run the `02_model_training.ipynb` notebook to train the predictive models (using algorithms like Logistic Regression, Random Forest, and XGBoost).
3. **Visualization:** Open the Tableau dashboard to visualize the insights and model performance.
