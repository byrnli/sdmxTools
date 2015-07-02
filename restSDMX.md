# ABS.Stat REST SDMX Webservice

The ABS.Stat REST SDMX webservice is a REST-like query interface for the [ABS.Stat](http://govhack.abs.gov.au) data warehouse.

It allows a programmer to easily call ABS.Stat using URL parameters to retrieve data and structures from ABS.Stat datasets.

All queries share the same general method of use, eg: `http:/govhack.abs.gov.au/restsdmx/sdmx.ashx/GetData/CPI/2+3.50.10001+20001.10+20.Q/ABS?startTime=2013&endTime=2015`

Here you can see each query starts with:
`http://govhack.abs.gov.au/restsdmx/sdmx.ashx/`

followed by the method, in this instance `GetData` and then the dataset code, `CPI`. After that are the parameters to the method.

 There are two methods available for use with the ABS.Stat REST SDMX webservice - `GetData` and `GetDataStructure`. 
 
####GetDataStructure
 
 The `GetDataStructure` method can be used to retrieve a listing of all available datasets, as well as the structure and codelists of individual datasets.
 
 `http://govhack.abs.gov.au/restsdmx/sdmx.ashx/GetDataStructure/ALL/ABS`
 
 `http://govhack.abs.gov.au/restsdmx/sdmx.ashx/GetDataStructure/CPI/ABS`
 
 
####GetData
