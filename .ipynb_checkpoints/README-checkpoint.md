# DentStats

AU Dentistry Dataset Statistics

## Overview

DentStats is a statistical analysis project for dentistry-related datasets. The project provides tools for data exploration, preprocessing, visualization, and statistical hypothesis testing using Python.

The analysis workflow includes:

* Data loading and management
* Exploratory data analysis (EDA)
* Statistical testing for categorical and numerical variables
* Data visualization
* Interpretation of results for dentistry research datasets

## Features

* Data manipulation and cleaning with Pandas
* Numerical computations with NumPy
* Data visualization using Matplotlib
* Chi-square tests for categorical variables
* Kruskal-Wallis tests for comparing multiple independent groups
* Mann-Whitney U tests for comparing two independent groups

## Requirements

```python
import os
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

from scipy.stats import chi2_contingency, kruskal, mannwhitneyu
```

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd DentStats
```

Install the required dependencies:

```bash
pip install numpy pandas matplotlib scipy
```

## Usage

Open the Jupyter Notebook and run the analysis:

```bash
jupyter notebook
```

## Statistical Methods

### Chi-Square Test of Independence

Used to determine whether there is a significant association between two categorical variables.

### Kruskal-Wallis H Test

A non-parametric method for testing whether samples originate from the same distribution across multiple groups.

### Mann-Whitney U Test

A non-parametric test used to compare differences between two independent groups.

## Project Structure

```text
DentStats/
│
├── clinical_statistics_outputs/
├── notebooks/
├── README.md
└── requirements.txt
```

## Output

The project may generate:

* Statistical summary tables
* Hypothesis test results
* Visualizations and plots
* Research-ready descriptive statistics

## License
This project is provided for educational and research purposes.

## Author
Metehan Ünal, PhD

