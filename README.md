# Stage IV Precipitation Cookbook

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers Stage IV Precipitation data analysis that can be employed in a variety of applications.

## Motivation
The 13 National Weather Service River Forecast Centers (RFCs) analyze multi-sensor precipitation observations from rain gauges, mesonet observations, and radar estimates to create stage IV precipitation analysis data.

Due to its high-resolution grid spacing, hourly Stage IV Precipitation is a highly beneficial tool for analyzing precipitation observations throughout the contiguous United States. Stage IV data is plotted on a 4 km by 4 km polar-stereographic grid, allowing for identification of discontinuities as a result of the operational process. Through walking through several notebooks, including rainfall distribution maps and time series (to come soon), those who follow this cookbook will develop a deeper understanding how to create publication-quality plots using Stage IV Precipitation data. 

## Authors

[Evan Belkin](http://github.com/evan-belkin), [Marian de Orla-Barile](https://github.com/mariandob), [Selena Ramos](https://github.com/Selenaramoswx), [Kimberly Riek](https://github.com/Kriek21), [Kathryn Rooney](https://github.com/kathrynrooney), [Kevin Tyle](https://github.com/ktyle),

### Contributors

<a href="https://github.com/ProjectPythia/stage-iv-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/stage-iv-cookbook" />
</a>

## Structure

Please go through Notebook #1. Additional notebooks will be available soon! 

### Notebook #1: Plotting Stage IV Precipitation Data from the National Center for Environmental Prediction (NCEP), Housed in Zarr Format by the United States Geological Survey (USGS)

This notebook will walk you through creating publicaiton-quaulity plots of the Stage IV precipitation data during a high-impact east coast Atmospheric River event.

### Additional Notebooks Coming Soon! 

These notebooks will include extracting precipitation data at a single grid point to create time series and performing a spatial average of the data over a smaller domain. We aim to publish these notebooks by the end of June 2025.

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:


1. Clone the `https://github.com/ProjectPythia/Stage-IV-Cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/Stage-IV-Cookbook.git
   ```

2. Move into the `Stage-IV-Cookbook` directory
   ```bash
   cd Stage-IV-Cookbook
   ```
3. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate Stage-IV-Cookbook
   ```
4. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
=======
