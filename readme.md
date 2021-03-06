The entire repository covers the technical assignment given by Blue Sky Analytics
It contains two folders:
1. Analysis: Contains the codes used for analysis as well as visualisation images as where needed
2. Results and Summary Report Slides: Contains the report for analysis and summary in both .pdf and .pptx (PowerPoint) formats

To replicate the notebooks, after cloning the repository:
1. Change directory to "Analysis" and run:
```
pip install -r requirements.txt
```
This will install the necessary libraries that were used for the assignment

The following tasks under the "Analysis" folder should be run in order with their notebooks:

**1. COVID19-Exploration**

This folder was used in identifying most affected developing country during the COVID-19 pandemic, India

**Notebooks to run:** COVID19_India.ipynb

**Datasets:**

- Covid19 Dataset (Worldwide cases 2019-20)
- GIS World Data File

**2. Impacts-of-COVID-19**

This folder was used to evaluate the environmental impacts of COVID-19 on mobility, air quality and water quality of India

**Notebooks to run in order of analysis:**

- Mobility.ipynb
- Air_Quality.ipynb
- Water_Quality.ipynb

**Datasets:**

- India_shape: for the geospatial view of South East Asia
- India_water: for the geospatial view of water bodies in India

**Useful results:**

- Water-Quality-pngs: for helpful visualisations from the analysis of water quality
- Air-Quality-jpgs: for helpful visualisations from the analysis of air quality

**3. AQI-Analysis**

**Notebooks to run in order of analysis:**

- AQI_Analysis.ipynb: for objectively verifying our results on air quality earlier, analysing the AQI across different cities in India
- AQI_ML.ipynb: for developing a machine learning model for predicting these time-series data on air quality

**Datasets:**
- air-quality-data-in-india: for the Air Quality Index (AQI) of India
- indian-cities-database: cities in India, to evaluate the AQI with respect to the cities

**Useful results:**
- AQL_ML_Prediction.png: visualise how well the ML model predicts time-series data
- pollutants.png: view pollutant levels over time


**NOTE:**
The important visualisations have been included in **"Blue Sky Assignment"**

- Results and Summary Report Slides:
This folder contains:
1. **Blue Sky Assignment (in .pdf/pptx):** This file contains the findings, details on the steps, visual and non-visual results extracted from the assignment
2. **Blue Sky - Summary Report (in .pdf/pptx):** This file contains the required summary report requested in the assignment

