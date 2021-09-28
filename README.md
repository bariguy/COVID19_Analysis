# COVID19_Analysis

### Description
* This repository contains several attempts in analyzing global trends and interesting correlations between specific features with regards to COVID-19 Pandemic. 
THe analysis was done using the following datasets. Detailed summaries of the datasets can be found below:

### Datasets 
 - _Our World in Data Global Data_: https://urldefense.com/v3/__https:/github.com/owid/covid-19-data/tree/master/public/data__;!!Et4lQkQVNeVVgw!J2jlVl58nX8A_X5P618BQ0GLCYPOL96EmMeeCMxZeq4yYaU14BDSyMxxcgVKK-cIRA$ 
 
-  _JHU Global Time Seires Data_: https://urldefense.com/v3/__https:/github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series__;!!Et4lQkQVNeVVgw!J2jlVl58nX8A_X5P618BQ0GLCYPOL96EmMeeCMxZeq4yYaU14BDSyMxxcgVX8AyTNw$

Datasets above were converted into 
```
owid-covid-data.csv
owid.xlsx
time_series_covid19_confirmed_US.xlsx
time_series_covid19_deaths_US.xlsx
```
for visual comprehension and familiarization. 

### ipynb Files
Following Jupyter Notebooks are found
```
csv_to_excel.ipynb
playing_around.ipynb
owid_analysis.ipynb
time_series_analysis.ipynb
```
_csv_to_excel.ipynb_ converts csv dataset into xlsx for visual comprehension.
_playing_around.ipynb_ contains multiple attempts and trials in order to familiarize myself with the data
_owid_analysis.ipynb_ contains detailed analysis with regards to _Our World in Data Global Data_. The analysis outlines interesting correlations between the the dataset's numerous features and COVID19 cases, globally. 
_time_series_analysis.ipynb_ exhibits a glimpse of an attempt in anlayzing a time series of COVID cases for US. This analysis file was meant to back up the analysis concluded in the _owid_analysis.ipynb_.
