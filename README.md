# Datasets for Visualization - Government Finance 2020

https://government-finance-e2d675.netlify.app/

## States data
* Object `data_from_dbsite.RDS` is generated from the ACFR PostgreSQL database. 
* States population 2020 is from Census: https://www.census.gov/programs-surveys/popest/technical-documentation/research/evaluation-estimates/2020-evaluation-estimates/2010s-state-detail.html
* `states.Rmd`: This file creates `states.csv` (compile ACFRs states data and Census). 

# Counties data
* `county_pop_census_acfrs.RDS`: Cleaning, matching ACFRs counties with population. 
This object is from `acfrs_census_matching_county_population.Rmd`. 
Repo: https://github.com/ReasonFoundation/acfrs_datachecking

* `counties.Rmd`: This file creates `counties.csv`


## Cities data
* `acfrs_city_pop_added_char.RDS`: Cleaning, matching ACFRs cities with census population. 
This object is from `acfrs_census_matching_cities_population.Rmd`
Repo: https://github.com/ReasonFoundation/acfrs_datachecking


* `cities.Rmd`: This file creates `cities.csv`

## School districts data
* `matched_acfrs_nces_sd.RDS`: Cleaning, matching ACFRs school districts with NCES students. 
This object is from `matching_acfrs_nces_school_districts.Rmd`
Repo: https://github.com/ReasonFoundation/acfrs_datachecking

* `districts.Rmd`: This file creates `district.csv`
