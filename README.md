# About

Climate Change has had a great impact on the globe's environment. One of these effects has been the increase of natural disasters. To address this issue, modern neural network architectures were trained on the International Monetary Fund's Climate Change Indicator Datasets [\[1\]](#Acknowledgments) to predict the number of natural disasters that occur in 30 different countries over a 28 year time-span. The models chosen were the Recurrent Neural Network, Long Short Term Memory, and LSTM with Attention.

All architectures were able to estimate the number of natural disasters, 4 years ahead, using climate change data. Results show that commonly known indicators, CO concentrations; surface temperature; end etc, that exhibit climate change does have an impact on the frequency of natural disasters.

# Getting Started

## Prerequisites
Install the below libraries for python files:
1. Pandas - For data manipulation and analysis.
Install with: pip install pandas
2. NumPy - For numerical operations on arrays.
Install with: pip install numpy
3. Scikit-learn - Provides tools for data preprocessing and splitting the dataset.
Install with: pip install scikit-learn
4. Keras - For building and training neural network models. Keras is now included within TensorFlow, so you will install TensorFlow to use Keras.
Install with: pip install tensorflow
5. Matplotlib - A comprehensive library for creating static, animated, and interactive visualizations in Python. Install with: pip install matplotlib
6. TensorFlow - This will enable you to use the Sequential model as well as layers like LSTM, Dense, and Dropout from TensorFlow's Keras API. This single installation will cover all the TensorFlow and Keras functionalities required for your script. Install with: pip install tensorflow
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

# Work distribution: 
1. Kevin Russell:
- Forward-Forward Continuous Model.
- Report Writer.
- Pre-processing of Data.
- Torch Batch DataLoader.
- Handling of Total Disasters and Surface Temperature.
- Project Management in Jira.
2. Sean Klein:
- Attention Neural Network.
- Simple RNN model.
- Pre-processing of Data.
- Report Writer.
- Initial Handling of Sea Levels and Co Concentration datasets.
- Project Leader.
3. Ataish Nehra:
- LSTM model.
- Report Writer.
- Pre-processing of Data.
- Initial Handling of Forest & Carbon  and Land Cover Accounts datasets.
- Sequencing the data set.
- Lead Programmer.


# Contributing

Please see the [contributing.md](Contributing.md) file for more details about how to contribute to the project.

# History

* 01_DataClean.ipynb (By: Kevin Russell)
	* This notebook loads the surface temperature dataset and climate disasters datasets to tidy the datasets into csv files. This file also evaluates what are the top 30 countries.

* 03_DataLoad.ipynb (By: Kevin Russell)
	* This notebook combines all datasets together, pre-process the datasets, sort the dataset by country and year, shift the dataset by 4 years, and replace na's with mean. This notebook also showcases the eda and cda performed on the datasets. Along with a simple fit of ridge regression.

# Folder Description:
1. Ataish LSTM model- Contains 3 python files, each file represents a different LSTM model along with a csv file i.e. the merged dataset used in all the 3 python files for building the ML model. Shows the worst model and the best performing model.
2. Clean Datasets- Consits of 2 subfolders- "other" that has cleaned files from the year 1992 to 2000 for various climate change measures and disaster data. The seconf subfolder- "top_30" has filtered data of only the top 30 countries according to the number of natural disasters occured(we have used this data for all our models).
3. Data Cleaning & Manipulation Scripts- This folder contails files for all the data scleaning done on independent data files of all the climate data as well as the natural disasters data.
4. Documentation- It has all the PDFs made on Overleaf, for our project and research work.
5. EDA & outlier detection- This folder contains python scripts for pre-machine learning EDA on the datasets along with outlier detection on the dataset, all done on jupyter python.
6. Presentation Slides- Consists of all the presentation files for our project.
7. Raw Datasets- It consists raw data files which were downloaded from International Monetary Fund's website. All of these are open source data and the link is entered in the "Acknowledgment" part.
8. Sean's Attention model - This folder has python scripts for attention neural network model, it has numerous files showing the progress of building different attention model and the final best performing model.
9. Images: It contains png files for all the EDA graphs.
# Contact
1. Ataish Nehra
   LinkedIn - http://www.linkedin.com/in/ataish-nehra
   GitHub - https://github.com/AtaishNehra
2. Sean Klein
   LinkedIn - https://www.linkedin.com/in/sean-klein-53b416264/
   GitHub - https://github.com/kleinse24
3. Kevin Russell
   LinkedIn - https://www.linkedin.com/in/kevin-russell-3b849087/
   GitHub - https://github.com/KLRussell
# Acknowledgments

1. [I. M. Fund. “Climate change data.” (), \[Online\]. Available: https://climatedata.imf.org/pages/climatechange-data. accessed: 03.07.2024.](https://climatedata.imf.org/pages/climatechange-data)
