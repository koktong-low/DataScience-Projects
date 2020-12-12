# Projects

This is a folder of projects I have done in the past:

### ![Share Price Analysis](https://github.com/koktong-low/DataScience-Projects/tree/main/Stocks)
There are many reasons as to why a share price would go up or down, it could be due to supply and demand, however it is much more complex than that. The goal of this project is to study various factors to see what kind of impact it has on share. Some of the factors we are investigating includes, relevant news, covid data, financial statements, and unemployment rate. We will be utilising skills from previous projects mainly NLP for the news classification, SVR for creating a predictive model, we would explore some deep learning to see if it is suitable as well. The data are web scraped from yahoo finance, and the COVID-19 Data are from https://github.com/owid/covid-19-data/tree/master/public/data . 

### Leverage Natrual Language Processing (NLP) for Automated Essay Scoring (AES)

According to Indeed.com a job site, an Australian teacher's average salary is AUD $64.71, and a 500-1000 word essay takes a teacher around 10 min to read (varies teacher to teacher). So a teacher can go through 6 essays/hour without breaks. In 2019 it was recorded that more than 40,000 students took the VCE (Victorian Certificate of Education) a state level exam in Australia, with 40,000 essays it would take approximately 6667 hours to grade these essays, which equates to AUD $431,400 just to grade essays.

So my team and I used NLP methods such as **BERT-SVR** and **LSTM** to develop an AES to reduce time required to grade essays.

### ![Using COVID data to better estimate and project earnings for Taxi companies of NYC](https://github.com/koktong-low/DataScience-Projects/tree/main/Covid_vs_Taxi)

COVID has no doubt affected the transport industry, due to this pandemic what was considered reliable projections of revenue from years of data has become rather inaccurate in these times of uncertainty. The following are the Geospatial visuialisations of Revenue and COVID cases of NYC taxi.

![Revenue & COVID Choropleth](/Covid_vs_Taxi/images/choropleth.png)


##### Download Interactive Map
![Revenue Choropleth](/Covid_vs_Taxi/Total_AmountChoroplethMap.html)

![COVID Choropleth](/Covid_vs_Taxi/CovidChoroplethMap.html)




#### Key models used
* Random Forest Regressor - had a very high prediction accuracy both validation (99%) and testing (98%) however it was not a good model to project data that was out of training temporal range (February 2020 - June 2020). The plot below shows that past june the prediction did not look good

![RFR Projection](/Covid_vs_Taxi/images//Projected_RFR_Revenue.png)

* Support Vector Regression - had a high prediction accuracy with both validation (95%) and testing (98%), this plot is a projection of taxi revenue for July 2020 - September 2020 

![SVR Projection](/Covid_vs_Taxi/images/Projected_SVR_Revenue.png)

##### Data Taken from:
* NYC COVID Borough - https://www1.nyc.gov/site/doh/covid/covid-19-data-boroughs.page
* NYC Yellow Taxi - https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page





