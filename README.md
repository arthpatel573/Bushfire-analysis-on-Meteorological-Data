# Bushfire analysis on Meteorological Data

The aim is to build statistical models that can predict the burned area of the bushfires. Specifically, the problem is to predict the burned area of a bushfire given the collected data and explain prediction and the associated findings.

# Dataset

The dataset contains 517 fire instances, each of which have 13 columns: the first 12 columns corresponding to the attributes (e.g., spatial coordinates, month, day, and other meteorological data) and the last column containing the burned area, i.e., the variable that we will predict. The details of the dataset can be found in the [original research paper](http://www3.dsi.uminho.pt/pcortez/fires.pdf). The dataset files are stored in UCI's website below. 

Forest fires data : There are two files on the website. One called \forest-fires.csv" contains the data needed for the analysis, and another called \forestfires.names" contains the information about the dataset.

In order to conduct the analysis, the provided `forest-fires.csv` is splitted into training dataset (80%) and testing dataset (20%) before building the models.

# Setup

Install all dependencies/packages mentioned in the `bushfire-analysis.ipynb` notebook.


Code successfully ran with R 3.5.0

