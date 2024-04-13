# About

Climate Change has had a great impact on the globe's environment. One of these effects has been the increase of natural disasters. To address this issue, modern neural network architectures were trained on the International Monetary Fund's Climate Change Indicator Datasets [\[1\]](#Acknowledgments) to predict the number of natural disasters that occur in 30 different countries over a 28 year time-span. The models chosen were the Recurrent Neural Network, Long Short Term Memory, and LSTM with Attention.

All architectures were able to estimate the number of natural disasters, 4 years ahead, using climate change data. Results show that commonly known indicators, CO concentrations; surface temperature; end etc, that exhibit climate change does have an impact on the frequency of natural disasters.

# Getting Started

## Prerequisites

## Installation

_Below is a step-by-step guide to install and setup the prediction models._

1. Clone the repository
   ```sh
   git clone https://github.com/AtaishNehra/Climate-Induced-Disaster-Predictor.git
   ```
2. Install notebook dependencies
   ```sh
   pip install -r requirements.txt
   ```
3. Install [GIT](https://git-scm.com/downloads)
4. Install Jupyter GIT Plugin
   ```sh
   pip install --upgrade jupyterlab jupyterlab-git
   ```

# Usage

_To use the repository's notebooks, you can launch the notebooks through Jupyter Notebook or through Jupyter Lab. Ensure that all required packages and software are installed before using the notebooks._

* Launch Jupyter Notebook
   ```sh
   python -m notebook
   ```
* Launch Jupyter Lab
   ```sh
   python -m jupyterlab
   ```

# Contributing

Please see the [contributing.md](CONTRIBUTING.md) file for more details about how to contribute to the project.

# History

* 01_DataClean.ipynb (By: Kevin Russell)
	* This notebook loads the surface temperature dataset and climate disasters datasets to tidy the datasets into csv files. This file also evaluates what are the top 30 countries.

* 03_DataLoad.ipynb (By: Kevin Russell)
	* This notebook combines all datasets together, pre-process the datasets, sort the dataset by country and year, shift the dataset by 4 years, and replace na's with mean. This notebook also showcases the eda and cda performed on the datasets. Along with a simple fit of ridge regression.

# Contact

# Acknowledgments

1. [I. M. Fund. “Climate change data.” (), \[Online\]. Available: https://climatedata.imf.org/pages/climatechange-data. accessed: 03.07.2024.](https://climatedata.imf.org/pages/climatechange-data)