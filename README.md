# Brazil-Real-Estate-Market
## Introduction
    This project is focused on the regional differences in the sales of apartment in brazil 
    and also look into the southern part of brazil to see if there is a relationship between home size and price. 
    The dataset was gotten from world quant datascience lab course and it contains two(2) csv files which was merged
    together during the wrangling process. The dataset contain 6 columns before the wrangling process and the names of 
    the columns are;
                  Property_type: This column contains two types of property which are apartment and house 
                  place_with_parent_names: This column the country-state-city
                  region: This column contains five regions i.e NorthEast, South, North, SouthEast,CentralWest
                  lat-lon: This column represent the latitude and longitude of each region
                  area_m2: This column represent the size of each property in m2 
                  price_usd: This column represent hthe price of each property.
## Data Cleaning
     The dataset had 2 csv file with different column heading, so i did a little cleaning before the csv files.
     For the first csv file,
            Dropped all nan values
            Splitted the lat-lon column into two i.e Lat, Lon and the dropped the lat-lon column
            Derived the state column  from the place-with-parent-names column and the dropped the place-with-parent-names
            Transformed the data type for the price-usd from string to float
    For the second csv file;
            Transformed the price_bri to price_usd using 3.19 bri to 1usd
            Dropped the price_bri column and also nan values
   After cleaning the two files, I concatenated it.
## Analysis & Findings
    The analysis for this project was performed using python and the details can be found in brazil-real-estate file.
    SouthEast had the highest mean price of apartment while SouthWest had the lowest mean price.
    Focusing on the southern part of brazil, we found a correllation betwen prices of an apartment and sizes across the states.
    
            
