## Data files for COMM318 _Stories from data_ Final Project

Data files are organized into 3 folders, where
* `Raw data` contains raw, uncleaned data files
* `Cleaned data` contains data files cleaned for later use
* `Others` contains data files that were not part of the analysis but were uploaded for data visualization or other purposes 

#### Raw data
* `world_suicide.csv`- suicide rates for male and female in each country from 2016,2015,2010, and 2000 (https://data.oecd.org/healthstat/suicide-rates.htm)
* `happy_index.csv`- happiness index data from Kaggle, 2016 (https://www.kaggle.com/mathurinache/world-happiness-report)
* `gdp.csv`- gdp data from the World Bank (https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)
* `work_hour.csv` - Average annual hours actually worked per worker by country, 2000-2019, data from OECD (https://data.oecd.org/emp/hours-worked.htm)
* `religion.csv` - Religious Composition by Country, 2010-2050, Pew Research Center (https://www.pewforum.org/2015/04/02/religious-projection-table/)
* `sunshine.csv` - table imported from wikipedia, list of cities by sunshine duration (https://en.wikipedia.org/wiki/List_of_cities_by_sunshine_duration)
* `depression.csv` - incidence (rate out of 100,000 people) of depression by countries in 2016, data from Global Health Data Exchange (http://ghdx.healthdata.org/gbd-results-tool)

#### Cleaned data
* `gdp_cleaned.csv` - the cleaned version of `gdp.csv`
* `world_total.csv` - a cleaned subset of `world_suicide` with aggregated suicide rates for both males and females 
* `country_to_region` - a subset of `happy_index` that maps countries to regions

#### Others
* `countries.geojson` - Geodata data package providing geojson polygons for all the world's countries (https://datahub.io/core/geo-countries)