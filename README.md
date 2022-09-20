# Astronomical Data in Python - UT FRI
*Astronomical Data in Python* is an introduction to tools and practices for working with astronomical data. This essentially is a bootstrapping mechanism for students wishing to work with these set of tools and practices for their projects in **CS 309: Geometry of Space (S)** and **CS 378: Geometry of Space (F)** courses. This introduction is a slightly modified version of the Allen Downing's [Introduction Toolset](https://www.google.com) of the same name.

Topics covered include:
* Writing queries that select and download data from a database.
* Using data stored in an Astropy `Table` or Pandas `DataFrame`.
* Working with coordinates and other quantities with units.
* Storing data in various formats.
* Performing database join operations that combine data from multiple tables.
* Visualizing data and preparing publication-quality figures.

As a running example, we will replicate part of the analysis in a recent paper, "[Off the beaten path: Gaia reveals GD-1 stars outside of the main stream](https://arxiv.org/abs/1805.00425)" by Adrian M. Price-Whelan and Ana Bonaca.

This material was developed in collaboration with [The Carpentries](https://carpentries.org/) and the Astronomy Curriculum Development Committee, and supported by funding from the American Institute of Physics through the American Astronomical Society.

> "I am grateful for contributions from the members of the committee" — Azalee Bostroem, Rodolfo Montez, and Phil Rosenfield — and from Erin Becker, Brett Morris and Adrian Price-Whelan.

The original format of this material is a series of Jupyter notebooks. Using the links below, you can read the notebooks on NBViewer or run them on Colab. If you want to run the notebooks in your own environment, you can download them from the repository and follow the instructions below to set up your environment.

This material is also available in the form of [Carpentries lessons](https://datacarpentry.org/astronomy-python/), but you should be aware that these versions might diverge in the future.

### Prerequisites

This material should be accessible to people familiar with basic Python, but not necessarily the libraries we will use, like Astropy or Pandas. If you are familiar with Python lists and dictionaries, and you know how to write a function that takes parameters and returns a value, that should be good enough.

We assume that you are familiar with astronomy at the undergraduate level, but we will not assume specialized knowledge of the datasets or analysis methods we'll use.

## Notebook 1

This notebook demonstrates the following steps:
1. Making a connection to the Gaia server,
2. Exploring information about the database and the tables it contains,
3. Writing a query and sending it to the server, and finally
4. Downloading the response from the server as an Astropy `Table`.

Look at [Notebook 1]() on Github
Run [Notebook 1](https://colab.research.google.com/github/AllenDowney/AstronomicalData/blob/main/01_query.ipynb) on Colab
or click here to read it on [NBViewer](https://nbviewer.org/github/AllenDowney/AstronomicalData/blob/main/01_query.ipynb)