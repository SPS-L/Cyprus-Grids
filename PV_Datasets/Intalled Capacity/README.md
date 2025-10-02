# Net Metering Installed Capacity Data Analysis

## Overview
This repository contains analysis of rooftop photovoltaic (PV) system installed capacity data from net metering installations. The analysis examines the distribution of single-phase and three-phase PV connections and performs statistical analysis to characterize the power capacity distributions.

## Dataset Description
- **File**: `Net_Metering_IC1.xlsx`
- **Variables**:
  - `Power`: Installed capacity in kW
  - `Phase`: Connection type (1-phase or 3-phase)
- **Total Records**: 17,692 installations

## Methodology
1. **Data Cleaning**: Remove records with missing power or phase information
2. **Descriptive Statistics**: Calculate counts and percentages of connection types
3. **Distribution Analysis**: Fit statistical distributions to power capacity data
4. **Goodness of Fit**: Use Akaike Information Criterion (AIC) to select best-fitting distributions
5. **Data Export**: Generate PMF and histogram data for further analysis

## Key Findings
- **Three-phase connections**: 9,408 installations (53.2%)
- **Single-phase connections**: 8,284 installations (46.8%)
- **Best-fitting distribution for single-phase**: Student's t-distribution
- **Best-fitting distribution for three-phase**: F-distribution

## Usage

### Running the Analysis
1. Place the `Net_Metering_IC1.xlsx` file in the same directory as the notebook
2. Run the Jupyter notebook `Net_Metering_IC1_Data_Analysis.ipynb`

## Applications
The generated data files can be used for:
1. **Monte Carlo Simulations**: PMF data enables probabilistic modeling of PV capacity distributions
2. **Power System Studies**: Histogram data supports load flow and stability analysis
3. **Policy Analysis**: Statistical distributions inform regulatory and incentive program design
4. **Grid Planning**: Capacity distributions guide infrastructure investment decisions
