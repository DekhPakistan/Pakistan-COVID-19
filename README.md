# Pakistan COVID-19 Dataset

This is the data repository for the 2019 Novel Coronavirus cases in Pakistan.

## Table of contents

 * [Daily reports (daily_reports)](#daily-reports-daily_reports)
 * [Combined report (combined_report)](#combined-report-combined_reportcsv)
 * [Data sources](#data-sources)

## [Daily reports (daily_reports)](https://github.com/DekhPakistan/Pakistan-COVID-19/tree/master/daily_reports)

This folder contains daily case reports. All timestamps are in UTC (GMT+0). Provincial Data is only available from 11th April 2020, previous reports have data of Pakistan as whole.

### File naming convention
YYYY-MM-DD.csv in UTC.

### Field description
* <b>Province_State</b>: Province, state or dependency name.
* <b>Country_Region</b>: Country, region or sovereignty name.
* <b>Last Update</b>: YYYY-MM-DD HH:mm:ss  (24 hour format, in UTC).
* <b>Lat</b> and <b>Long_</b>: Latitude and Longitude locations on the map. All points shown on the map are based on geographic centroids, and are not representative of a specific address, building or any location at a spatial scale finer than a province/state.
* <b>Confirmed</b>: Counts include confirmed and probable (where reported).
* <b>Deaths</b>: Counts include confirmed and probable (where reported).
* <b>Recovered</b>: Recovered cases are estimates based on local media reports, and state and local reporting when available, and therefore may be substantially lower than the true number.
* <b>Active:</b> Active cases = total cases - total recovered - total deaths.
* <b>Incident_Rate</b>: Incidence Rate = cases per 100,000 persons.
* <b>Case_Fatality_Ratio (%)</b>: Case-Fatality Ratio (%) = Number recorded deaths / Number cases.
* All cases, deaths, and recoveries reported are based on the date of initial report.

## [Combined report (combined_report.csv)](https://github.com/DekhPakistan/Pakistan-COVID-19/tree/main/combined_report.csv)

This file contains all the daily cases reports combined into one.

## Data sources
* [Government of Pakistan](http://covid.gov.pk/stats/pakistan)
* [JHU CSSE COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19)
