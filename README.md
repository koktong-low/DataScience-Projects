# Projects

This is a folder of projects I have done in the past:

### Using COVID data to better estimate and project earnings for Taxi companies of NYC

COVID has no doubt affected the transport industry, due to this pandemic what was considered reliable projections of revenue from years of data has become rather inaccurate in these times of uncertainty.

#### Key models used
* Random Forest Regressor - had a very high prediction accuracy both validation (99%) and testing (98%) however it was not a good model to project data that was out of training temporal range (February 2020 - June 2020). The plot below shows that past june the prediction did not look good

![RFR Projection](/Covid_vs_Taxi/images//Projected_RFR_Revenue.png)

* Support Vector Regression - had a high prediction accuracy with both validation (95%) and testing (98%), this plot is a projection of taxi revenue for July 2020 - September 2020 

![SVR Projection](/Covid_vs_Taxi/images/Projected_SVR_Revenue.png)

##### Data Taken from:
* NYC COVID Borough - https://www1.nyc.gov/site/doh/covid/covid-19-data-boroughs.page
* NYC Yellow Taxi - https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page





