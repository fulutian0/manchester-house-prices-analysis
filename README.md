# Manchester House Prices Analysis

This repository contains the Jupyter notebook and data files for analyzing the relationship between house prices and building ages in Manchester. The analysis includes data cleaning, statistical modeling, and data visualization.

## Project Overview

The aim of this project is to investigate whether there is an association between the age of buildings and house prices in Manchester. The analysis uses open data sources, combines and cleans the data, and applies statistical methods to quantify the relationship. The results are presented through both spatial and non-spatial visualizations.

## Repository Contents

- `201696622.ipynb`: The main Jupyter notebook containing the analysis.
- `price.xlsx`: The dataset containing house price information.
- `old.xlsx`: The dataset containing building age information.
- `README.md`: This file.

## How to Run the Project

1. **Clone the repository:**
    ```bash
    git clone https://github.com/fulutian0/manchester-house-prices-analysis.git
    cd manchester-house-prices-analysis
    ```

2. **Install the required Python packages:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Open the Jupyter notebook and run all cells:**
    ```bash
    jupyter notebook 201696622.ipynb
    ```

## Data Sources

- House prices data:  https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads
- Building ages data: https://epc.opendatacommunities.org 

## Analysis Steps

1. **Data Cleaning:**
    - Loaded and cleaned the house prices and building ages datasets.
    - Merged the datasets based on common fields.
    - Handled missing values and formatted the data for analysis.

2. **Exploratory Data Analysis:**
    - Described the data distribution and characteristics.
    - Visualized initial insights and relationships between variables.

3. **Statistical Modeling:**
    - Applied Ordinary Least Squares (OLS) regression to quantify the relationship between house prices and building ages.
    - Interpreted the model results and validated assumptions.

4. **Data Visualization:**
    - Created a spatial visualization using Folium to map house prices and building ages.
    - Developed a non-spatial visualization using Seaborn to show the coefficients and confidence intervals from the regression model.

## Visualization Details

- **Spatial Visualization:**
    - The map is generated using Folium and displays circles representing house prices and building ages.
    - Circle size indicates the house price, and color represents the building age band.
    - A legend is included to explain the color scheme and circle sizes.

- **Non-Spatial Visualization:**
    - A bar plot shows the coefficients and confidence intervals from the OLS regression model.
    - Colors and labels are used to make the plot accessible and easy to interpret.


## Contact

For any questions or issues, please contact ml22y3z@leeds.ac.uk.

