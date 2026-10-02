<div align="center">

# ETL Data Cleaning & Transformation Utilities

### Automated Python framework for cleaning, normalizing, and validating relational datasets

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-data%20analysis-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**An automated ETL preprocessing framework designed to clean, transform, and normalize noisy relational datasets.**

</div>

---

## Overview

This repository contains Jupyter notebooks for building and executing ETL data cleaning pipelines in Python. It provides repeatable data validation constraints, robust type casting, missing value handling, and feature preparation workflows using optimized vectorized operations.

The notebooks serve as interactive environments to inspect dirty datasets, apply transformation steps, and export clean, standardized data.

## Repository structure

```text
.
├── 01_cleanig_Data copy.ipynb
├── Data_Cleanig.ipynb
└── README.md
```

## Topics and workflows

The notebooks explore core data wrangling and preprocessing techniques, including:

- **Missing Value Imputation:** Strategies for detecting and filling or dropping null values across numeric and categorical features.
- **Data Type Normalization:** Casting raw fields into proper data types (dates, floats, integers, categories).
- **Text & Column Cleanup:** Standardizing column headers, removing leading/trailing spaces, and normalizing string representations.
- **Outlier & Duplicate Removal:** Identifying redundant entries and filtering anomalies or bad inputs.
- **Pipeline Export:** Exporting fully validated datasets into structured, ready-to-use analytical formats.

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Pandas and NumPy

Install the required packages using `pip`:

```bash
python -m pip install pandas numpy notebook
```

On Windows, if `python` is not recognized, use `py`:

```powershell
py -m pip install pandas numpy notebook
```

## Getting started

1. Clone this repository:

   ```bash
   git clone https://github.com/Qureshiii/etl-data-cleaning-utils.git
   cd etl-data-cleaning-utils
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `Data_Cleanig.ipynb` or `01_cleanig_Data copy.ipynb` to execute and explore the data cleaning workflow.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
