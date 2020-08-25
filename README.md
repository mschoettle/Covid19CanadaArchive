# COVID-19 Data from Canadian Government Sources

This repository provides automated, daily backups of COVID-19 data from various Canadian government sources.

**File name timestamps are given in ET (America/Toronto) in the following format: %Y%-m-%d_%H-%M.** The script is run nightly around 23:00 ET.

## Sources/terms of use

The sources and terms of use for each included dataset are linked below.

### Alberta

* [COVID-19 Alberta statistics](https://www.alberta.ca/stats/covid-19-alberta-statistics.htm): See “data notes” tab
    * To be added
* [COVID-19 in Alberta: Current cases by local geographic area (Edmonton)](https://data.edmonton.ca/Community-Services/COVID-19-in-Alberta-Current-cases-by-local-geograp/ix8f-s9xp): [City of Edmonton Open Data Terms of Use](https://data.edmonton.ca/stories/s/City-of-Edmonton-Open-Data-Terms-of-Use/msh8-if28/)
    * ab/edmonton-cases-by-areas/COVID-19_in_Alberta__Current_cases_by_local_geographic_area.csv

### British Columbia

* [BC COVID-19 Data](http://www.bccdc.ca/health-info/diseases-conditions/covid-19/data): [Disclaimer and data notes](http://www.bccdc.ca/Health-Info-Site/Documents/BC_COVID-19_Disclaimer_Data_Notes.pdf)
    * Case data: bc/case-data/BCCDC_COVID19_Dashboard_Case_Details.csv
    * Laboratory data: bc/laboratory-data/BCCDC_COVID19_Dashboard_Lab_Information.csv

### Canada

* [Coronavirus disease 2019 (COVID-19): Epidemiology update](https://health-infobase.canada.ca/covid-19/epidemiological-summary-covid-19-cases.html): [Open Government Licence - Canada](https://open.canada.ca/en/open-government-licence-canada)
    * can/epidemiology-update/covid19.csv

### Ontario

* [Confirmed positive cases of COVID19 in Ontario](https://data.ontario.ca/dataset/confirmed-positive-cases-of-covid-19-in-ontario/resource/455fd63b-603d-4608-8216-7d8647f43350): [Open Government Licence – Ontario](https://www.ontario.ca/page/open-government-licence-ontario)
    * on/confirmed-positive-cases/conposcovidloc.csv
* [Status of COVID-19 cases in Ontario](https://data.ontario.ca/dataset/f4f86e54-872d-43f8-8a86-3892fd3cb5e6/resource/ed270bb8-340b-41f9-a7c6-e8ef587e6d11): [Open Government Licence – Ontario](https://www.ontario.ca/page/open-government-licence-ontario)
    * on/status-of-cases/covidtesting.csv
* [City of Toronto COVID-19 Summary](https://www.toronto.ca/home/covid-19/covid-19-latest-city-of-toronto-news/covid-19-status-of-cases-in-toronto/): [Open Government Licence – Toronto](https://open.toronto.ca/open-data-license/)
    * To be added
* [COVID-19 Cases in Toronto](https://open.toronto.ca/dataset/covid-19-cases-in-toronto/): [Open Government Licence – Toronto](https://open.toronto.ca/open-data-license/)
    * To be added
