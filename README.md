# Data-Curation-Project-I310D
My goal for this project was to use python to successfully scrape and convert tabular web data into a DataFrame where I could clean the dataset before visualizing into a graph depicting the relationship between two columns of data.

For this project, I used Wikipedia's list of [deadly earthquakes since 1900](https://en.wikipedia.org/wiki/List_of_deadly_earthquakes_since_1900) as my dataset to scrape. I used BeautifulSoup to find and scrape the HTML table on Wikipedia, Pandas to convert the data into a DataFrame, and Seaborn to visualize the relationship between Countries / Territories that have had earthquakes since 2000 and their magnitude. 

## Analysis

As described above, my data illustrates the relation between countries and territories that have had earthquakes since 2000, their magnitude, and amount, all organized into a catplot. Through my plot we can see countries like Indonesia, China, Iran, and Turkey are most susceptible to earthquakes, with Indonesia, Japan, Peru, and Chile suffering some of the worst earthquakes in last milennia. 


## Potential biases
The data has been taken from Wikipedia, which can be edited by anyone. I cannot verify if any vandalism has been done to the data source and has made it unreliable.

## Data Dictionary
| Column name | Type | Description |
| ----------- | ---- | ----------- |
| Present-day Country / Territory | String | The present-day country / territory where the earthquake occured. |
| Lat | Decimal | The latitude of the earthquake. |
| Long | Decimal | The longitude of the earthquake. |
| Depth (km) | Decimal | The depth (in kilometers) of the earthquake. |
| Secondary Effects | String | The secondary effects that occurred as a result of the earthquake. F - Fire, T - Tsunami, L - Landslide, Lq - Liquefaction |
| PDE Shaking Deaths | Decimal | The number of deaths caused by earthquake shaking as determined by the United States Geological Survey’s Preliminary Determination of Epicenters (PDE) monthly listing. |
| PDE Total Deaths | Decimal | The number of total deaths caused by an earthquake as determined by the United States Geological Survey’s Preliminary Determination of Epicenters (PDE) monthly listing. |
| Utsu Total Deaths | Decimal | The number of total deaths caused by an earthquake measured by Seismologist Tokuji Utsu's ""Catalog of Damaging Earthquakes in the World". |
| EM-DAT Total Deaths | Integer | The number of total deaths caused by an earthquake as measured by the Emergency Events Database (EM-DAT). |
| Other Source Deaths | String | Earthquake shaking deaths listed from detailed reports and other scholarly sources where available. |



## APIs used
- [BeautifulSoup](https://launchpad.net/beautifulsoup)
- [Pandas](https://pandas.pydata.org/docs/index.html)
- [Seaborn](https://seaborn.pydata.org/)
- [Requests](https://requests.readthedocs.io/en/latest/)

## Source of Data
- [Wikipedia - List of deadly earthquakes since 1900](https://en.wikipedia.org/wiki/List_of_deadly_earthquakes_since_1900)

## License
- [MIT](https://github.com/utsav-nimavat/Data-Curation-Project-I310D/blob/ec1f19bc1a7b80f10abf77dc52ca6c885f918d33/LICENSE)

