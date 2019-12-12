# Systematic review of descriptions of novel bacterial species: evaluation of the XXI century taxonomy through text mining

This repository contains a collection of Jupyter Notebooks for extracting information from textual content of abstracts of bacterial descríptions published between 2001 and 2018, which were downloaded from Pubmed.

## Prerequisites

All scripts were written in Python 3 language, and they are provided as Jupyter notebooks (an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text).

The scripts need the following Python 3 libraries:
- Biopython
- Pandas
- Seaborn
- Matplotlib
- NLTK

The easiest way to install them will be through Conda (https://docs.conda.io/en/latest/miniconda.html).
Once Miniconda is installed, you may need to first run these commands to install Jupyter and Python libraries:

```
conda install -c anaconda jupyter
conda install -c conda-forge biopython 
conda install -c anaconda pandas 
conda install -c anaconda seaborn 
conda install -c conda-forge matplotlib
conda install -c anaconda nltk
```

## Installing

```
git clone https://github.com/fhsantanna/bibliometrics
cd bibliometrics
```

## Running the scripts
Start the Jupyter server with the following command:
```
jupyter notebook
```
In the opened web browser (http://localhost:8888), go to the folder "bibliometrics" and open the desired notebook.


## Description of each notebook

Explain what these tests test and why

## Author

* **Dr. Fernando Hayashi Sant'Anna** - [fhsantanna](https://github.com/PurpleBooth)