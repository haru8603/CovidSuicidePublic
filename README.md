# Covid Suicide
Replication code for **"The Effect of Voluntary Staying at Home on Japanese Female Suicide during the COVID-19 Pandemic"**. 

All codes are written in Stata18 and run in Jupyter Notebook. 

The data are available upon request to the corresponding authors.

# Install

1. Install the latest version of Python, Stata 18.0, and Jupyter Notebook. Note that Stata older than Stata 18.0 may not work in  Jupyter Notebook.
    - Main packages in Stata 18.0
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
    
   or download in a zip
   
   ![image](https://github.com/haru8603/CovidSuicidePublic/assets/38587774/d6f45e72-f433-4e1b-ae16-eec43be33354)

3. Put data that we provide upon request into ```data``` folder  **by yourself**.

# Folder Structure
- ```main```: Storage code for estimation, figures, and tables.
- ```data```: Storage cleaned data.
- ```figuretable```: Storage figures and tables.
