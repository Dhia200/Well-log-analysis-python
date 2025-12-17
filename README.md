# Well Log Analysis Using Python

## Objective
This project demonstrates a Python-based petrophysical workflow applied to well log data. The objective is to read LAS files, perform basic petrophysical calculations, and visualize results using industry-standard log plots.

## Dataset
Public well log data provided in LAS format. The dataset contains Gamma Ray, Resistivity, Density, and auxiliary porosity logs.

## Methodology
The following steps were implemented:
- LAS file parsing using the `lasio` library
- Data quality control and handling of missing values
- Volume of Shale (Vsh) estimation using the Gamma Ray index method
- Density-derived porosity calculation using standard rock and fluid assumptions
- Triple-combo log visualization combining lithology, resistivity, and porosity information

## Results
The analysis identifies intervals characterized by low shale volume, elevated resistivity, and moderate-to-good porosity values. These intervals exhibit petrophysical signatures consistent with clean reservoir-quality formations.

## Tools
- Python
- lasio
- pandas
- numpy
- matplotlib

## Notes
All calculations are based on standard petrophysical assumptions and are intended for demonstration and learning purposes.
