# Python_data_covid-19
Using  OpenDataPhilly covid-19 information, I'm using it as an opportunity to practice my Python whilst maybe finding something information.  

## OpenDataPhilly
[OpenDataPhilly Homepage](https://www.opendataphilly.org/)  
[OpenDataPhilly Covid Dataset Search](https://www.opendataphilly.org/dataset?q=covid)

### From Their Webpage
> We help departments share data from city government with the public on OpenDataPhilly. Access to data, like City payments, property assessments, and 311 service requests makes government more transparent.  

#### How To Make Requests to OpenDataPhilly
> This dataset is published to carto, which allows you to query the data using SQL (specifically the PostgreSQL flavor with the PostGIS extension). Rather than executing the queries in a database program, you execute them through HTTP (ie. the web browser) via Carto's SQL API, passing your query as the q parameter. For example:  
``` https://phl.carto.com/api/v2/sql?q=SELECT * FROM covid_cases_by_date ```  
**You can do just about everyting you'd expect from a PostgreSQL+PostGIS database - even joins between tables.**  
