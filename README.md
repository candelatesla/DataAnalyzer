# Streamlit Data Explorer

A simple and interactive web application for exploratory data analysis and visualization, powered by Streamlit and pandas.

## Overview

Streamlit Data Explorer is a lightweight web app that enables users to:
- Upload CSV or Excel datasets
- Visualize data using line, bar, and scatter charts
- Perform basic descriptive statistics
- Carry out simple data operations such as dropping columns

It is ideal for analysts and students looking for an easy way to understand and explore their data without writing code.

## Features

- **Dataset Upload:** Support for CSV and Excel files  
- **Data Visualization:** Interactive selection of columns for line, bar, and scatter plots  
- **Descriptive Statistics:** Quick summary statistics for selected columns  
- **Data Operations:** Drop columns interactively and update the dataset  
- **User-Friendly UI:** Navigate between Home, Visualization, Analysis, and Data Operations via sidebar navigation  

## Getting Started

### Prerequisites

- Python 3.8+
- Required packages:
  ```
pip install streamlit pandas
  ```

### Usage

1. Clone the repository:
  ```
  git clone https://github.com/candelatesla/DataAnalyzer.git
  cd DataAnalyzer
  ```
2. Run the app:
  ```
  streamlit run dwm.py
  ```
3. Open your browser to the Streamlit URL provided in the terminal to start uploading, analyzing, and visualizing your data.

## File Structure

- `dwm.py` — Main Streamlit application

## Example

After running the app, upload your dataset and use the navigation to visualize or analyze columns, or drop columns you don't need.

## License

MIT License — Free to use and modify.
