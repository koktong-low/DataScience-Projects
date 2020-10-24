# Projects

This is a folder of projects I have done in the past:

### Leverage Natrual Language Processing (NLP) for Automated Essay Scoring (AES)

According to Indeed.com a job site, an Australian teacher's average salary is AUD $64.71, and it a 500-1000 word essay takes a teacher around 10 min to read (varies teacher to teacher). So a teacher can go through 6 essays/hour without breaks. In 2019 it was recorded that more than 40,000 students took the VCE (Victorian Certificate of Education) a state level exam in Australia, with 40,000 essays it would take approximately 6667 hours to grade these essays, which equates to AUD $431,400 just to grade essays.

So my team and I used NLP methods such as **BERT-SVR** and **LSTM** to develop an AES to reduce time required to grade essays.

### ![Using COVID data to better estimate and project earnings for Taxi companies of NYC](https://github.com/koktong-low/DataScience-Projects/tree/main/Covid_vs_Taxi)

COVID has no doubt affected the transport industry, due to this pandemic what was considered reliable projections of revenue from years of data has become rather inaccurate in these times of uncertainty.

#### Key models used
* Random Forest Regressor - had a very high prediction accuracy both validation (99%) and testing (98%) however it was not a good model to project data that was out of training temporal range (February 2020 - June 2020). The plot below shows that past june the prediction did not look good

![RFR Projection](/Covid_vs_Taxi/images//Projected_RFR_Revenue.png)

* Support Vector Regression - had a high prediction accuracy with both validation (95%) and testing (98%), this plot is a projection of taxi revenue for July 2020 - September 2020 

![SVR Projection](/Covid_vs_Taxi/images/Projected_SVR_Revenue.png)

##### Data Taken from:
* NYC COVID Borough - https://www1.nyc.gov/site/doh/covid/covid-19-data-boroughs.page
* NYC Yellow Taxi - https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page





