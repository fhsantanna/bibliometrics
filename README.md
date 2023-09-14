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
* Unpack the zip files

## Running the scripts
Start the Jupyter server with the following command:
```
jupyter notebook
```
In the opened web browser (http://localhost:8888), go to the folder "bibliometrics" and open the desired notebook.


## Description of the files

* "sp_nov_2001_2018_pubmed_16012019.medline" - raw input in medline format

* "sp_nov_2001_2018_pubmed_16012019_ed.xml" - raw input in XML format

* "table_1_eligible.csv" - curated table containing eligible records

* "DSMZ_bactnames.csv" - DSMZ Prokaryotic Nomenclature up-to-date in CSV format (August 2019)

* "all_data_eligible_records.csv" - curated table containing all data from the eligible records


## Description of the notebooks

* Notebook 1 - Organize the data of the MEDLINE file in a table (fields Journal, Title, Abstract, Authors and Year). Filter out erratas, comments, responses, descriptions of Candidatus or protist species, and items with publication dates of 2019 or without abstracts from the final dataset. Input: "sp_nov_2001_2018_pubmed_16012019.medline"

* Notebook 2 - Count the number of items of each journal. Count the number of items per author. Input: "table_1_eligible.csv"

* Notebook 3 - Extract and count species, genus and phylum names. Generate word cloud. Input: "table_1_eligible.csv"

* Notebook 4 - Count and plot the word frequency of the abstracts. Input: "table_1_eligible.csv"

* Notebook 5 - Identify the first author's country. Plot production by country per year.  Inputs: "sp_nov_2001_2018_pubmed_16012019_ed.xml" and "table_1_eligible.csv"

* Notebook 6 - Count and plot the bigram frequency of the abstracts. Input: "table_1_eligible.csv"

* Notebook 7 - Count and plot the number of described species per year. Input: "DSMZ_bactnames.csv"

* Notebook 8 - Verify and count valid names. Inputs: "DSMZ_bactnames.csv", "table_1_eligible.csv" and "freq_species.csv"


## Author

* **Dr. Fernando Hayashi Sant'Anna** - [fhsantanna](https://github.com/fhsantanna)
