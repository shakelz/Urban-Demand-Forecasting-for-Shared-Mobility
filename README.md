# Urban Demand Forecasting for Shared Mobility

This repository contains the source code, notebooks, datasets, figures, and supplementary materials for the research paper:

**Cross-Modal Shared Mobility Demand Forecasting**

## Authors

- Abdul Shakeel Mohammed
- Raja Hashim Ali
- Shan Faiz
- Iftikhar Ahmed
- Talha Ali Khan
- Ali Zeeshan Ijaz

## Abstract

This repository accompanies the journal paper proposing a cross-modal forecasting framework for shared mobility demand prediction. The framework combines historical demand, weather, calendar, holiday, and neighborhood-context information to improve forecasting accuracy while providing explainability, transferability analysis, and operational decision support.

## Repository Structure

```
data/
    Raw and processed datasets

notebooks/
    Jupyter notebooks for all experiments

src/
    Source code

Outputs/
    Generated figures, tables, and experimental results
```

## Installation

```bash
pip install -r requirements.txt
```

## Dataset

The experiments use the publicly available UCI Bike Sharing Dataset.

https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/shakelz/Urban-Demand-Forecasting-for-Shared-Mobility.git
cd Urban-Demand-Forecasting-for-Shared-Mobility
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook:
   UDF CODE.ipynb

```text


5. Outputs will be saved in:

```text
Outputs/Figures/
Outputs/Tables/

```

## Reproducing the Paper Results

To reproduce the full set of results, run all notebooks from top to bottom without skipping cells. The notebooks generate the figures, tables, metrics, and prediction results reported in the manuscript.

## License

This project is released under the MIT License.
