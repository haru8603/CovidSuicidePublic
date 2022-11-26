# Covid Suicide
Replication code for **"The impact of reduced mobility on suicide during the COVID-19 pandemic"**. 

All code are written in Stata17 and run in Jupyter Notebook. 

The data are available on request to corresponding authors.

# Install

1. Install Stata 17.0, the latest version of Python, and Jupyter notebook. Note that Stata older than Stata 17.0 may not work in notebook.

2. Clone this repository into your local environment by 

```git clone git@github.com:haru8603/CovidSuicidePublic.git```

# Folder Structure
- ```main```: Storage code for estimation, figures, and tables.
- ```data```: Storage cleand data.
- ```figuretable```: Storage figure and table in Latex format.

# Code Structure
- ```estimate_main_result```: Make estimation results in the section 4. 
  - Export estimation results in Latex format.
- ```estimate_robustness```: Make estimation results in the section 5. 
  - Export estimation results in Latex format.
- ```make_figure```: Make figures in the main text and appendix.
  - Note that pre-trend figure is in ```estimate_main_result``` and specification curve figure in ```estimate_robustness```. 
- ```appendix```: Run additional estimation and tables in the online appendix section A. 
  - Export estimation results in Latex format.

# Table and Figures
- Figure 1 
- Figure 2
- Figure 3 
