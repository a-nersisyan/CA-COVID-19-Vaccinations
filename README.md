# CA-COVID-19-Vaccinations

### Research Questions
Casual Inference - Does a higher median household county income level cause a higher proportion of COVID-19 vaccination?
GLM/Non-Parametric - Do demographics (age, race/ethnicity, and gender) predict the rate of receiving a COVID-19 vaccine?
___
### Folder Hierarchy
- COVID-19: contains datasets from the COVID-19 Vaccine Progress Dashboard Data by the Calfornia Department of Public Health
- vaccines_county.csv: dataset containing the daily vaccine counts for California counties
- vaccines_demographics.csv: dataset containing the daily vaccine demographics for California as a whole
- GADM USA: contains the spatial data of administrative areas in the U.S. by GADM. Despite there being 16 files, we only use 1
- gadm36_USA_2.shp: dataset containing the geometric coordinates of all administrative areas in the U.S.
- ca_pop_sex_age.csv: American Community Survey dataset containing estimates of the total resident population and resident population age 18 years and older for California in 2019
- county_pop.csv: California Department of Finance dataset containing the total population for each county in 2018
- education.csv: USDA Economic Research Service dataset containing the average percent of county residents that completed college in 2015-2019
- income.csv: American Community Survey dataset containing the median household income for each county in 2018 dollars
- requirements.txt: contains packages required to download
