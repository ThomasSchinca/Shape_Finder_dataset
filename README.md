# Shape_Finder_dataset

## Three dataset examples
1. Conflict-Fatalities.csv: Monthly conflict fatalities from Ukraine, Sudan, and Ethiopia, extracted from the UCDP Dataset (source: https://ucdp.uu.se/downloads/).
2. Inflation.csv: Monthly inflation at the country level (source: https://www.worldbank.org/en/research/brief/inflation-database).
3. Temperatures.csv: Monthly mean temperatures at the country level, extracted from ERA-5 satellite data (source: https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=form).
   
## Your csv dataset format 
Any kind of dataset is compatible with ShapeFinder. But it should follow a few rules:
- It should be a csv file
- The first columns should be the date of the TS in a date format if you want the plot to print the right date. However, just numbers would be printed
- All the cases, countries, or object of studies should be added in columns
- The length of columns an rows are limited
