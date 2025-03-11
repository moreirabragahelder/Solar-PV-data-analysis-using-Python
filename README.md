# Photovoltaic Data Analysis

## Overview
This project analyzes photovoltaic cell data, extracting key electrical parameters such as open-circuit voltage (VOC), short-circuit current density (JSC), maximum power point (Pmax), fill factor (FF), and power conversion efficiency (PCE). The script processes experimental data stored in Excel files and computes these metrics for multiple solar cells.

## Features
- **Data Loading**: Reads raw photovoltaic measurement data from Excel files.
- **Data Processing**: Filters relevant data and calculates key performance metrics.
- **Visualization**: Generates plots for current-voltage (J-V) characteristics.
- **Results Export**: Stores computed parameters in a structured DataFrame.

## Requirements
Make sure you have the following dependencies installed before running the notebook:

```bash
pip install pandas numpy matplotlib jupyter
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/photovoltaic-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd photovoltaic-analysis
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `analysis.ipynb` and run the cells step by step.

## File Structure
```
photovoltaic-analysis/
│── data/	# Raw data files (Excel)
│── Solar PV data analysis using Python.ipynb	# Jupyter Notebook for analysis
│── requirements.txt	# Dependencies
│── README.md	# Project documentation
```

## Results
The script generates:
- **VOC**: Open-circuit voltage for each cell.
- **JSC**: Short-circuit current density.
- **Pmax**: Maximum power output.
- **FF**: Fill factor calculation.
- **PCE**: Efficiency of the solar cell.

## Contribution
Feel free to contribute by submitting pull requests or opening issues for improvements.

## License
This project is licensed under the MIT License.

