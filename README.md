# Analysing-OS-Kernel-Vulnerabilities-main
# OS Kernel Vulnerabilities Analysis

## Overview
This project performs an exploratory data analysis (EDA) of operating system (OS) kernel vulnerabilities using data from the National Vulnerability Database (NVD). The analysis focuses on trends in discovery rates, severity, affected operating systems, and common vulnerability types from 2020 to 2025.

## Authors
- Nipun Juneja
- Nishant Rajora

## Features
- Load and process CVE data from JSON files.
- Identify kernel-related vulnerabilities.
- Analyze temporal trends in vulnerability discoveries.
- Visualize severity distributions and OS breakdowns.
- Classify vulnerabilities by type based on descriptions.
- Generate insights on the most severe vulnerabilities.

## Requirements
To run this project, you need the following Python packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `tqdm`
- `scikit-learn`

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn tqdm scikit-learn
