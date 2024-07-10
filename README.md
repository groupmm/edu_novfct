<img src="https://github.com/groupmm/edu_novfct/blob/main/data/Edu_NovFct_Teaser.png" alt="edu_novfct logo" width="1000">

# Education Novelty Function (ENF) Notebooks

> A Basic Tutorial on Novelty and Activation Functions for Music Signal Processing

This repository contains [Jupyter Notebooks](https://jupyter.org) that include [Python](https://www.python.org) source code and audio excerpts for reproducing and experimenting with the examples discussed in the tutorial:

Meinard Müller and Ching-Yu Chiu.
<b>A Basic Tutorial on Novelty and Activation Functions for Music Signal Processing.</b>
Transaction of the International Society for Music Information Retrieval (TISMIR), ??: ??–??, 2024.

## Installation Guide

### Setting Up a Conda Environment
You can establish a conda environment by employing the ``edu_novfct.yml`` file. This approach includes necessary packages like `jupyter` to facilitate running demo notebooks. Run the following command:

```
conda env create -f edu_novfct.yml
```

## Running Example Notebooks
To explore ``ENF`` notebooks:

1. **Clone the repository:** Download the ``edu_novfct`` repository to your local machine using the following git command:
   
```
git clone https://github.com/groupmm/edu_novfct.git
```

2. **Install Jupyter:** If not already installed via the conda environment setup, install Jupyter to run the notebooks:

```
pip install jupyter
```

3. **Launch Jupyter Notebook:** Start the Jupyter notebook server by executing: 
```
jupyter notebook
```
This will open a browser window from where you can navigate to and open the example notebooks.

## Contributing

We are happy for suggestions and contributions.  We would be grateful for either directly contacting us via email (meinard.mueller@audiolabs-erlangen.de) or for creating an issue in our GitHub repository. Please do not submit a pull request without prior consultation with us.

## License

The code for this repository is published under an [MIT license](LICENSE). This does not apply to the data files:
* Audio files are taken from the [FMP notebooks](https://www.audiolabs-erlangen.de/resources/MIR/FMP/C0/C0.html).

## Acknowledgements

The [International Audio Laboratories Erlangen](https://audiolabs-erlangen.de/) are a joint institution of the 
[Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU)](https://www.fau.eu/) and [Fraunhofer Institute for 
Integrated Circuits IIS](https://www.iis.fraunhofer.de/en.html).
