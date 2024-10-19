# US Health Insurance Coverage by Race/Ethnicity (2022) - Interactive Data Visualization

This project visualizes the 2022 Health Insurance Coverage data by race and ethnicity across each US state using Plotly's scatter_mapbox. It features an interactive map that allows users to explore coverage disparities and trends across different demographics.

## Preview
![Interactive Map](interactive-map.gif)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data)
- [Contributing](#contributing)
- [License](#license)

## Overview

The interactive map enables users to select different racial and ethnic groups to see state-specific data, including coverage types and the number of insured individuals. Each state's data can be viewed in detail through tooltips that appear on hover, which include the state's name, coverage type, number of people covered, and the specific race/ethnicity. This interactive approach not only enhances the user experience but also provides a platform for in-depth analysis of health insurance coverage disparities and trends across different demographics at a state level.


## Features

- **Interactive Dash Map**: Visualize health insurance data geographically on a map.
- **Dropdown for Race/Ethnicity Selection**: Users can filter the map view based on the race/ethnicity.
- **Custom Tooltips**: Hovering over any state shows details such as state name, coverage type, number of people covered, and race/ethnicity.
- **Jupyter Notebook Integration**: All functionalities are integrated within a Jupyter Notebook using Dash and JupyterDash libraries.

## Technologies Used

- **Python**: Primary programming language.
- **Jupyter Notebook**: Environment for writing and sharing code dynamically.
- **Dash and JupyterDash**: Frameworks for building interactive web applications directly in Python.
- **Plotly**: Library for interactive and complex visualizations.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.

## Installation

1. **Clone the Repository**

  ```bash
   git clone https://github.com/acorvin/health-insurance-coverage-by-race-ethnicity.git

   cd health-insurance-coverage-by-race-ethnicity
  ```

2. **Install Required Libraries**:

  ```bash
   pip install -r requirements.txt
  ```

3. **Launch Jupyter Notebook**:

  ```bash
   jupyter notebook
  ```

Navigate to the notebook file within the Jupyter interface to open and run it.

## Usage

After installing the dependencies and launching Jupyter Notebook, open the `analysis.ipynb` file and run the cells sequentially to activate the interactive visualization.

## Data Sources

[SHADAC analysis of the American Community Survey (ACS) Public Use Microdata Sample (PUMS) files.](https://statehealthcompare.shadac.org/table/29/health-insurance-coverage-type-by-race-ethnicity#2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52/39,40,41,42,238,43,239,1,8,6/42/58)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
"""