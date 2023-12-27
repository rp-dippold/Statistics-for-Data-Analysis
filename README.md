# Statistics-for-Data-Analysis
This repository contains the final project of Udacity's "Statistics for Data Analysis" Nanodegree.

## Installation, Dependencies and Starting the Notebook
The code of this project was tested on Linux (Ubuntu 20.04). To get the code running on your local system, follow these steps which are base on Anaconda, pip and git:

### Download Repository
1. Go to a folder where you want to clone the repository
2. In a bash terminal enter `git clone https://github.com/rp-dippold/Statistics-for-Data-Analysis.git`

### Setting up Python environment
Enter the following commands in a bash terminal:
1. `cd Statistics-for-Data-Analysis`
2. `conda create --name statdataanalysis python=3.10.10 -c conda-forge`
3. `conda activate statdataanalysis`
4. `python -m pip install --upgrade pip`
5. `python -m pip install -r requirements.txt`
7. `python -m ipykernel install --user --name statdataanalysis --display-name "statdataanalysis"`

### Start a Jupyter Notebook
1. Navigate to the project's folder.
2. Start the notebook by entering `jupyter-notebook` into the bash terminal.
3. Copy one of the displayed URLs, e.g. 'http://127.0.0.1:8888/?token=78c...' in a browser tab.
4. Select the notebook `project.ipynb` in your browser.
5. Select the kernel "statdataanalysis" before running the cells.
