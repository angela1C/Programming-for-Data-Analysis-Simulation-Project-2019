# Programming_for_data_analysis_Project at GMIT 2019


This repository contains my submission for the Programming for Data Analysis Module 2019 Project for the Programming for Data Analysis module at GMIT as part of the Higher Diploma in Computing and Data Analytics.
This repository contains the Jupyter notebook `Simulate.ipynb` and some related data files and folders. The main body of the work is in the notebook.

## Problem statement:
For this project you must create a data set by simulating a real-world phenomenon of your choosing. You may pick any phenomenon you wish – you might pick one that is of interest to you in your personal or professional life. Then, rather than collect data related to the phenomenon, you should model and synthesise such data using Python. We suggest you use the numpy.random package for this purpose.
Specifically, in this project you should:
- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible.
- Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.
Note that this project is about simulation – you must synthesise a data set. Some students may already have some real-world data sets in their own files. It is okay to base your synthesised data set on these should you wish (please reference it if you do), but the main task in this project is to create a synthesised data set. The next section gives an example project idea.



## How to download this repository

Go to the URL for the repository on GitHub at https://github.com/angela1C/Programming_for_data_analysis_Project Click the green Clone or download button.

### Contents of this repository:

 - This readme file
 - The simulation.ipynb notebook containing the research and analysis of the actual data and the implementation of the simulation.
 - data folder containing any datasets that are used in this project. This folder also contains csv files which were created as part of this project. 
 - reports folder containing reports from the World Happiness Report website.
 - additional notesbooks that were created as part of the development of this project will be removed.


Python 3 was used to develop this project and is needed to run the code in the notebook. Python 3 can be downloaded from the official Python website at https://www.python.org/downloads/. It can also be downloaded using the Anaconda Python distribution at https://www.anaconda.com/distribution/.

The Jupyter Notebook `simulation.ipynb` itself can be viewed directly in this GitHub repository in a browser without Python 3 being installed. On occasion the Jupyter Notebook may not render correctly in which case the url https://github.com/angela1C/Fundamentals_Data_Analysis_Project-2019 can be copied and pasted in to the Jupyter nbviewer at https://nbviewer.jupyter.org where you enter the location enter the location of a Jupyter Notebook and click Go to have it rendered there.

The notebook containing all the work is called `simulation.ipynb`. If the repository is downloaded it can be run locally by navigating to the folder and entering the command jupyter lab or jupyter notebook on the command line. This will open Jupyter in the browser. The notebook can be opened then within the Jupyter session. Once opened you can can select Restart Kernel and Run All from the Run or Kernel menu. You can also run the selected cells and advance through the notebook using the run icon. The code should be run from top to bottom. The main python libraries used pandas, seaborn, matplotlib.pyplot and numpy are loaded at the beginning of the notebook. These are part of the anaconda distribution of python. Any additional libraries used are loaded within the relevant section of the notebook.


## Overview of the Notebook

The first section introduced the project and outlined the real world phenomenon I have chosen to simulate.
The next section loaded a real world dataset on which the simulation would be based. There is a bit of cleaning in this section to get the data ready. Several datasets were loaded and merged. The prepared data is then written to csv to the data folder of this repository.
The next section focused on analysing the real world dataset, looking at the type of variables, their distributions and their relationships with other variables in the data.
The final section then prepares for the simulation and implements the simulation of the dataset.

Note that part of the requirement for this project was to have all the work relating to the project detailed in the jupyter notebook. For this reason the notebook may take a little while to load. 

## References 
References are noted in the section in which they are used and are listed at the end of the notebook.
There are some references listed which are not used directly in the notebook but which were used to gain an understanding of the topics involved. 
