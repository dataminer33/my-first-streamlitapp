## Overview

The Streamlit app visualizes and filters the auto MPG dataset, showcasing the relationship between engine size (displacement) and highway fuel mileage. It also includes a map visualization of car sharing data.

## Features

- **Scatter Plot**: Displays a scatter plot of engine size versus highway fuel mileage, with the option to show class means.
- **Interactive Selectors**: Users can choose a specific year from the dropdown and toggle whether to show class means on the scatter plot.
- **Plot Type**: Users can switch between Matplotlib and Plotly plots.
- **Streamlit Map**: Displays a map with car sharing data, showing the locations where cars are shared.

## Dependencies

- Streamlit
- pandas
- matplotlib
- plotly
- urllib
- json
- copy

## Usage

To run this project, follow these steps:

1. Ensure all the dependencies are installed. You can install them using `pip`:

```bash

pip install streamlit pandas matplotlib plotly

Download the auto MPG dataset (mpg.csv) and place it in the data/ directory.
Run the Streamlit app by executing the Python script:

streamlit run app.py

Data
The dataset used in this project is the auto MPG dataset from UCI Machine Learning Repository, sourced from UCI Machine Learning Repository.

Contributing
Contributions to this project are welcome. Please follow these guidelines when submitting a pull request:

Ensure that your code adheres to the project's style guidelines.
Include tests for any new features or changes.
Document any new features or changes in the README.md.
License
This project is licensed under the MIT License. ```
