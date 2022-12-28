# Covid Suicide
Replication code for **"The impact of reduced mobility on suicide during the COVID-19 pandemic"**. 

All codes are written in Stata17 and run in Jupyter Notebook. 

The data are available upon request to the corresponding authors.

# Install

1. Install the latest version of Python, Stata 17.0, and Jupyter Notebook. Note that Stata older than Stata 17.0 may not work in  Jupyter Notebook.
    - Main packages in Stata 17.0
        - reghdfe: version 6.12.2
        - ivreghdfe: version 1.1.1
        - ivreg2: version 4.1.11
        - coefplot: version 1.8.4
        - esttab: version 2.1.0
        - speccurve: 1.13 from (<a href="url">https://github.com/martin-andresen/speccurve</a>)
    - Main packages in Python
        - stata_setup: version 0.1.2
       
2. Clone this repository into your local environment by 

    ```git clone git@github.com:haru8603/CovidSuicidePublic.git```
    
   or download in zip
   
    ![image](https://user-images.githubusercontent.com/38587774/204181995-4ee83d06-7825-45e6-8340-4fb9c49e702c.png)

3. Put data that we provide upon request into ```data``` folder  **by yourself**.

# Folder Structure
- ```main```: Storage code for estimation, figures, and tables.
- ```data```: Storage cleaned data.
- ```figuretable```: Storage figure and table in Latex format.

# Code Structure
- ```estimate_main_result```: Make estimation results in section 4. 
  - Export estimation results in Latex format.
- ```estimate_robustness```: Make estimation results in section 5. 
  - Export estimation results in Latex format.
- ```make_figure```: Make figures in the main text and appendix.
  - Note that the pre-trend figure is in ```estimate_main_result``` and the specification curve figure in ```estimate_robustness```. 
- ```appendix```: Run additional estimation and tables in the online appendix section A. 
  - Export estimation results in Latex format.

