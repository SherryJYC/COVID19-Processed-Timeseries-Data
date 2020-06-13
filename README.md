# COVID19-Processed-Timeseries-Data
* When using COVID-19 data and SARS data for time series and map visualization, data preprocessing took us a long time
* Those processed files can be directly used for visualization, e.g upload to Flourish or display on Mapbox directly

## Purpose
* Provide processed COVID-19 data (China) and SARS data (China) with geo-information
* Make processed data more suitable for visualizations like time series chart or map with timeline
* Help comparision between COVID-19 and SARS

## Data Sources
* COVID-19 data: [DXYArea.csv](https://github.com/BlankerL/DXY-COVID-19-Data/blob/master/csv/DXYArea.csv) from [COVID-19/2019-nCoV Infection Time Series Data Warehouse](https://github.com/BlankerL/DXY-COVID-19-Data)
> This data warehouse is based on [DXY](https://ncov.dxy.cn/ncovh5/view/pneumonia)
* SARS data: 

## Description of Data
### COVID-19 data
* number of confirmed, cured and dead cases for 375 areas/cities
* time range: from Jan 24 to May 7 2020
* additional fields: latitude, longitude
* notice: missing data (dates are not continuous) are filled by the value of previous day.

### SARS data
* number of confirmed, cured and dead cases for 27 provinces
* time range: from Mar 31 to Aug 16 2003
* additional fields: latitude, longitude
* notice: missing data (dates are not continuous) are filled by the value of previous day.

## Other Sources about COVID-19
* China <br/>
[COVID-19/2019-nCoV Infection Time Series Data Warehouse](https://github.com/BlankerL/DXY-COVID-19-Data) <br/>

* Global <br/>
[Open COVID-19 Dataset](https://github.com/open-covid-19/data) <br/>
[GIS for worldwide situation provide by JHU](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)


