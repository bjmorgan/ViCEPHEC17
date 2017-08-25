# ViCEPHEC17 - Python / Jupyter Workshop

# Evolving Python coding in lab classes to enhancing student understanding of key kinetic concepts in tutorials

Benjamin J. Morgan & Fiona Dickinson

[![DOI](https://zenodo.org/badge/101063504.svg)](https://zenodo.org/badge/latestdoi/101063504)

This repository contains Jupyter notebooks for the ViVE PHEC 2017 workshop.

The notebooks can be viewed using [nbviewer](http://nbviewer.jupyter.org/):

- [ViCE Intro 2017](http://nbviewer.jupyter.org/github/bjmorgan/ViCEPHEC17/blob/master/ViCE_intro_2017.ipynb)
- [SSA Simulation](http://nbviewer.jupyter.org/github/bjmorgan/ViCEPHEC17/blob/master/SSA_simulation.ipynb)
- [Competing Equilibria](http://nbviewer.jupyter.org/github/bjmorgan/ViCEPHEC17/blob/master/Competing%20Equilibria.ipynb)
- [Maxwell-Boltzmann](http://nbviewer.jupyter.org/github/bjmorgan/ViCEPHEC17/blob/master/Maxwell-Boltzmann.ipynb)

Interactive versions of the notebooks can be launched using [binder](http://mybinder.org):  
[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/repo/bjmorgan/ViCEPHEC17)  
We recommend you download this repository and run Jupyter on your own machine for the best experience.

## Getting started (Anaconda)

Although the example Jupyter notebooks can be viewed using the links above, they are best run interactively in Jupyter. The simplest way to do this is to download [Anaconda](https://www.continuum.io/downloads). Download this repository, by selecting `Clone or download > Download ZIP` at the top of this page. Extract the downloaded ZIP archive. Then launch Anaconda, and launch Jupyter. This opens Jupyter in your web browser, with a view of your filesystem. Navigate to where you unzipped this reposutory, and get started by opening the `ViCE_intro_2017.ipynb` notebook.

## Getting started (command line)

If you have `pip` running from the command line, you can install Jupyter using `pip install jupyter`. Download this repo using `git clone https://github.com/bjmorgan/ViCEPHEC17.git`. Go into the new `ViCEPHEC17` directory and launch Jupyter with `jupyter notebook`. Get started by opening the `ViCE_intro_2017.ipynb` notebook, or go straight to the first tutorial example `SSA simulation.ipynb`. You might need to install additional Python modules. If so, follow the `Requirements` instructions below.

## Requirements

- numpy
- scipy
- matplotlib

If these are not already installed on your system, you can install using the included `requirements.txt` file:

```
pip install -r requirements.txt
```

