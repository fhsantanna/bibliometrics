# Systematic review of descriptions of novel bacterial species: evaluation of the XXI century taxonomy through text mining

This repository contains a collection of Jupyter Notebooks for extracting information from textual content of abstracts of bacterial descríptions published between 2001 and 2018, which were downloaded from Pubmed.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

All scripts were written in Python 3 language, and they are provided as Jupyter notebooks (an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text).

The scripts need the following Python 3 libraries:
- Bioconda
- Pandas
- Seaborn
- Matplotlib
- NLTK
- [Affiliation Parser](https://github.com/titipata/affiliation_parser) 

The easiest way to install them will be through Conda (https://docs.conda.io/en/latest/miniconda.html).
Once Miniconda is installed, you may need to first run these commands to install Jupyter and Python libraries (Affiliation Parser must be installed independently):

```
conda install -c anaconda jupyter
conda install -c bioconda bioconda-utils
conda install -c anaconda pandas 
conda install -c anaconda seaborn 
conda install -c conda-forge matplotlib
conda install -c anaconda nltk
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
