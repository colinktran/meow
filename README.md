# Flow Cytometry Analysis
This repo contains my first experiment in visualizing and automating the analysis of flow cytometry data starting with an introduction to various data analysis tools.
Tools used in this analysis include FlowCytometryTools, fcsparser, pandas, numpy, scipy, matplotlib, and seaborn.
The main project folder, flow_analysis, contains four files used to run this experiment: 
venv/  # Python virtual environment,
First experiment.ipynb  # Jupyter Notebook with initial analysis,
requirements.txt  # Python dependencies for reproducing the experiment,
run_analysis.sh  # Shell script to activate venv, install dependencies, and launch Jupyter,
# Clone the repository
'''bash
git clone https://github.com/colinktran/meow.git
cd meow
# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate
# Install dependencies
pip install -r requirements.txt
# Launch Jupyter Notebook
jupyter notebook
