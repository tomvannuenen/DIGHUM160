# DIGHUM160: Digital Hermeneutics

![logo](img/backdrop-color.jpg)

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Ftomvannuenen%2Fdighum160&urlpath=lab%2Ftree%2Fdighum160%2F) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the Jupyter Notebooks for DIGHUM160: Critical Digital Humanities, at the [UC Berkeley Digital Humanities Summer Minor](https://summerdigitalhumanities.berkeley.edu/).

## Course Summary
This course confronts hermeneutic philosophy with computational text analysis. Hermeneutics refers to a long-standing intellectual tradition in the humanities that focuses on the theory and methods of interpretation.

In the lectures and discussions, we will deal with leading hermeneutic philosophers such as Hans-Georg Gadamer and Don Ihde, focusing on issues such as dialogicality, reflexivity, and the scientific status of technologically mediated interpretation. The other half of the course involves project-based research using Python to analyze interactions in communities on social news website Reddit.

# Course Requirements
You are not expected to have prior programming knowledge, and you are not graded on your coding skills. However, this course does make extensive use of Jupyter Notebooks and Python code, so previous exposure to Python will be highly beneficial.

## Installation Instructions

Before attending the workshop, you should install Python and Jupyter on your computer. If you need help, please make sure to come to the weekly seminar (see bCourses for more information).

Anaconda is software that allows you to run Python and Jupyter Notebooks on your computer. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda](https://www.anaconda.com/downloads). Click "Skip registration" and then download the Distribution for your machine. 

If you have a Mac, make sure to download the correct distribution for either Apple Silicon (for M1-M3 chips) or Intel (for Intel chips; typically, these can be found in pre-2021 MacBooks). If you don't know which chip you have, click on the Apple icon on your screen, click on "About This Mac", and look under "Chip". 

2. Download the materials in this repository: Go into your terminal and type `git clone https://github.com/tomvannuenen/DIGHUM160.git`

3. You can create a new environment and install the package dependencies using the following terminal command (after navigating to the `DIGHUM160` folder):

```bash
conda env create -f environment.yml
```

4. To activate your new conda environment, you can use the following command:

```bash
conda activate dighum
```

5. To create a Jupyter kernel for this new environment:

```bash
python -m ipykernel install --user --name=dighum
```


## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time.   

2. Click the "Launch" button under "Jupyter Lab" and navigate through your file system to the `DIGHUM160` folder you downloaded above.
Alternatively, type into your terminal:

```bash
jupyter lab
```

3. Navigate to the "Notebooks" folder, and to "Week0".

4. Open the `Python_Basics.ipynb` file to begin.

5. Press Shift + Enter (or Ctrl + Enter) to run a cell.

## Is Python not working on your laptop?

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, you can use the UC Berkeley DataHub to run the materials for these lessons. You can access the DataHub by clicking this button:

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Ftomvannuenen%2Fdighum160&urlpath=lab%2Ftree%2Fdighum160%2F)

The DataHub loads this repository and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No Python installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and click on the `DIGHUM160` folder.


## Directories & Files

- **notebooks/**  Your Jupyter Notebooks, including accompanying video's on what is happening in them. You are expcted to swap out data with your own as soon as possible when using these.

- **data/**  The Data directory contains several example datasets we will work through.

- **img/**  Has the images used throughout this repository.

- **.gitignore**  A file for ignoring changes to this repository

- **README.md**  Contains the text on this page.

- **requirements.txt**  Python libraries needed to run this repo.

## DH Summer Minor

Learn more about the Berkeley Digital Humanities Summer Minor: https://summerdigitalhumanities.berkeley.edu/
