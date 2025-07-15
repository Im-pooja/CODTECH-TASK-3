# CODTECH Internship: Task 3 - Data Visualization

## Overview
This repository contains the code and output for Task 3 of the CODTECH internship, focusing on interactive data visualizations using Python and Plotly. The analysis uses the `simple-zipcodes.csv` dataset and a synthetic dataset of 100,000 rows to demonstrate scalability.

## Files
- `Task3_DataVisualization.ipynb`: Jupyter Notebook with code for generating synthetic data and interactive visualizations.
- `task3_output.txt`: Expected output descriptions for each code cell.
- `simple-zipcodes.csv`: Original dataset used for schema and sampling.
- `zip_by_state.html`, `top_cities.html`, `record_by_state.html`: Interactive Plotly visualizations.
- `Task3_DataVisualization.html`: Exported notebook with embedded plots.

## Setup Instructions
1. Install dependencies: `pip install pandas plotly jupyter`
2. Run the notebook in Jupyter: `jupyter notebook`
3. View outputs in `task3_output.txt` and HTML files for interactive plots.

## Analysis Summary
- **Zip Code Distribution**: Near-uniform across states (~16,500-16,700 records).
- **Top Cities**: Cities like ASHEBORO and MESA dominate (~5,500-5,600 records).
- **Validation**: Scatter plot confirms uniform RecordNumber distribution.

## Notes
Due to issues with PySpark execution, this task uses Pandas and Plotly for reliable visualization. Outputs are provided as HTML files and described in `task3_output.txt`.
