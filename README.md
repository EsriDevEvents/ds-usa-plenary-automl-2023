# Using AutoML to predict Rideshare demand

This demo shows the use of ArcGIS Notebooks, the ArcGIS Python libraries (ArcGIS API for Python/ArcPy), open-source Python libraries, and the new AutoML tool within the GeoAI toolbox to model rideshare demand in Chicago, USA, then make predictions in several other US cities.  The original idea for this demo was derived from the following 2 papers:

Yan, X., Liu, X., & Zhao, X. (2020). Using machine learning for direct demand modeling of ridesourcing services in Chicago. _Journal of Transport Geography_, 83, 102661. https://doi.org/10.1016/j.jtrangeo.2020.102661

Li, Z. (2022). Extracting spatial effects from machine learning model using local interpretation method: An example of shap and xgboost. _Computers, Environment and Urban Systems_, 96, 101845. https://doi.org/10.1016/j.compenvurbsys.2022.101845

## Materials

This [ArcGI Pro project package](https://esriis-my.sharepoint.com/:u:/r/personal/nich7905_esri_com/Documents/DevSummit2023_AutoML_PlenaryDemo_April2023.ppkx?csf=1&web=1&e=Kyiidn) contains the notebook, two maps (Chicago and Philadelphia) and a geodatabase containing all required data except data source #1 (the rideshare CSV).  All necessary data sources have been vetted and are listed in Section 7 of the notebook.

## Other notes

 - Step 2 of the notebook: Read in the rideshare CSV downloaded from Data source #1.  Take note of the cell execution times for many of the steps in Step 2.  This CSV has 110 million records, so some of the cell executions can take up to 15 to 20 minutes.

 - Step 3 of the notebook: Read in the EPA SLD database, filtered by city.  Do steps 3.1 through 5 (model training) with the Chicago data.  Then repeat steps 3.1 through 4.1 with any other city's data that you want to make predictions on.

- Step 6 of the notebook: This step is only performed on the other cities that you want to make predictions on.

## Video recording

A recording of this demo begins at roughly the 1hr 27min mark of the Plenary, Day 2: Spatial Analytics, Extending and Automating the ArcGIS System video here: https://devsummit2023.esri.com/flow/esri/23epcdev/deveventportal/page/sessions/session/1671655603342001ILJH

Most of the recordings are uploaded to [2023 Esri Developer Summit in "mediaspace.esri.com"](https://mediaspace.esri.com/channel/2023%2BEsri%2BDeveloper%2BSummit/292702072) and slides are made available at [Esri Events > Proceedings](https://www.esri.com/en-us/about/events/index/proceedings).
