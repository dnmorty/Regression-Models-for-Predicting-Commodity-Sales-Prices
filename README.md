## Regression Models for Predicting Commodity Sales Prices
![image of corn](../assets/corn_image.png)
This folder contains all of the files relevant to my BrainStation Capstone Project:
***Regression Models for Predicting Commodity Sales Prices***
by Daniel Mortensen

### Subfolder Layout
- Raw data is stored in the "./Data" subfolder.
- All dataframes generated during the importing, cleaning, exploring, or other analysis steps are stored in the "./DataFrames" subfolder.
- Requirements for setting up the different kernels used in this project are stored in the "./kernel requirements" subfolder.
- PDF printouts of the Jupyter notebooks used for this project are stored in the "./PDF Versions of Notebook Files" subfolder.

### Project Notebooks
- "Data Scrubbing.ipynb": used for scrubbing and combining corn, market, and climate data into unified dataframes and for engineering a baseline feature.
- "Data Visualization and Exploratory Analysis.ipynb": used for visualizing the various features and exploring their relevance to the target feature, "PRICE RECEIVED, MEASURED IN $ / BU".
- "Modeling.ipynb": used for testing various machine learning regression models for predicting the target feature, "PRICE RECEIVED, MEASURED IN $ / BU".

### References
- Corn data was taken from: https://quickstats.nass.usda.gov/
- Climate data was taken from: https://www.ncdc.noaa.gov/cag/national/time-series
- US Population data was taken from: https://www.multpl.com/united-states-population/table/by-year