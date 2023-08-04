## BSRProject
BSR-Project-AmrLab-DSpath

Project Description: 
The primary objective of the BSR project is to establish a standard set of benchmark datasets for evaluating and comparing the performance of spatial regionalization algorithms. By providing diverse datasets and comprehensive evaluations, this project aims to contribute to the development of more effective and efficient spatial regionalization techniques.


Project Tasks:
The following tasks will be performed in order as time permits, completing all of the tasks is recommended. However, we will adjust based on the time schedule.


Data Collection: Gather a rich and diverse set of spatial datasets from various sources, including US census data and data from other countries where spatial polygon data is available. Consider different combinations of variables, such as population density, income levels, and land-use types.
\
\
Data Preprocessing: Clean and preprocess the datasets to ensure consistency and compatibility with various spatial regionalization algorithms.
\
\
Algorithm Selection: Identify and implement a range of spatial regionalization algorithms for evaluation and comparison from the existing techniques in the literature.
\
\
Benchmarking: Run the selected spatial regionalization algorithms on the compiled benchmark datasets and record their performance in terms of accuracy, efficiency, and other relevant metrics.
\
\
Analysis and Comparison: Analyze the results and compare the performance of different spatial regionalization algorithms across the benchmark datasets. Identify trends, strengths, and weaknesses, and suggest potential improvements for the algorithms.
\
\
Documentation: Prepare a detailed report and presentation summarizing the project's findings and contributions to the spatial regionalization research community.




## Data descriptions

## LAcity

| Column Name | DataType | Description                                                                    |
|-------------|----------|--------------------------------------------------------------------------------|
| fid         | float64  | Unique identifier for each record in dataset                                   |
| OBJECTID    | int64    | Unique identifier for each object or entity in dataset                         |
| TRACTCE10   | object   | FIPS code for census tract; geographic area used for reporting statistical alt |
| POP         | int64    | Population count                                                               |
| LATPOP_D    | int64    | Latino/Hispanic population                                                     |
| WHIPOP_D    | int64    | White population                                                               |
| BLAPOP_D    | int64    | Black population                                                               |
| AMIPOP_D    | int64    | American Indian/Alaska Native population                                       |
| ASIPOP_D    | int64    | Asian population                                                               |
| HPIPOP_D    | int64    | Hawaiian/Pacific Islander population                                           |
| OTHPOP_D    | int64    | Other race population                                                          |
| MMRPOP_D    | int64    | Multiple race population                                                       |
| VAP         | int64    | voting age population                                                          |
| LATVAP_D    | int64    | Latino/Hispanic voting age population                                          |
| WHIVAP_D    | int64    | White voting age population                                                    |
| BLAVAP_D    | int64    | Black voting age population                                                    |
| AMIVAP_D    | int64    | American Indian/Alaska Native voting age population                            |
| ASIVAP_D    | int64    | Asian voting age population                                                    |
| HPIVAP_D    | int64    | Hawaiian/Pacific Islander voting age population                                |
| OTHVAP_D    | int64    | Other race voting age population                                               |
| MMRVAP_D    | int64    | Multiple race voting age population                                            |
| H0010001    | int64    | Total housing units                                                            |
| H0010002    | int64    | Number of occupied housing units                                               |
| H0010002    | int64    | Number of occupied housing units                                               |
| H0010002   | int64   | Number of occupied housing units                                                 |                                                                                                    
| H0010003   | int64   | Number of vacant housing units                                                                                  
| TOOLTIP    | object  | Additional information or description related to the data point                                                                                                                                     |
| NLA_URL    | object  | A URL or web address pointing to more information about the Census tract                                                                                                                            |
| STATEFP10  | object  | State FIPS code                                                                                                                                                                                     |
| COUNTYFP10 | object  | County FIPS code                                                                                                                                                                                    |
| TRACTCE10_ | object  | Another version of Census tract code                                                                                                                                                                |
| GEOID10    | object  | Unique FIPS code that combines the state, county, and tract code for  each tract; concatenation of STATEFP10, COUNTYFP10, and TRACTCE10                                                             |
| NAME10     | object  | 2010 Census tabulation block name; a concatenation of "Block", Census state Federal Information Processing Standards (FIPS) code, county FIPS  code, census tract code, and tabulation block number |
| NAMELSAD10 | object  | Extended name of census tract                                                                                                                                                                       |
| MTFCC10    | object  | The MAF/TIGER Feature Class Code, a code indicating the type of  geographic feature represented by the data.                                                                                        |
| FUNCSTAT10 | object  | functional status code defines the current functional status of a  geographic entity                                                                                                                |
| ALAND10    | float64 | Area of census tract that is land                                                                                                                                                                   |
| AWATER10   | float64 | Area of census tract that is water                                                                                                                                                                  |
| INTPTLAT10 | object  | latitude coordinate of the locator of the census tract                                                                                                                                              |
| INTPTLON10 | object  | longitude coordinate of the locators of the census tract                                                                                                                                            |
| Tot_Pop    | float64 | Total population count                                                                                                                                                                              |
| One_Race   | float64 | One race population count                                                                                                                                                                           |
| White      | float64 | White population count                                                                                                                                                                              |
| Afro_Amer  | float64 | Black population count                                                                                                                                                                              |
| Native     | float64 | Native American population count                                                                                                                                                                    |
| Asian      | float64 | Asian population count                                                                                                                                                                              |
| Pac_Isl    | float64 | Hawaiian/Pacific Islander population count                                                                                                                                                          |
| Other_Race | float64 | Other race population count                                                                                                                                                                         |
| Two_Or_Mor | float64 | 2+ race population count                                                                                                                                                                            |
| Hispanic   | float64 | Hispanic/Latino population count                                                                                                                                                                    |
| Not_Hisp   | float64 | NonHispanic/Latino population count                                                                                                                                                                 |
| Hisp_One_R | float64 | Hispanic/Latino population that identifies with one race                                                                                                                                            |
| Hisp_White | float64 | Hispanic/Latino population that identifies as White                                                                                                                                                 |
| Hisp_Afro_ | float64 | Hispanic/Latino population that identifies as Black                                                                                                                                                 |
| Hisp_Nativ | float64 | Hispanic/Latino population that identifies as Native American/Alaska Native                                                                                                                         |
| Hisp_Asian | float64 | Hispanic/Latino population that identifies as Asian                                                                                                                                                 |
| Hisp_Pac_I | float64 | Hispanic/Latino population that identifies as Hawaiian/Pacific Islander                                                                                                                             |
| Other      | float64 | Hispanic/Latino population that identifies as other races                                                                                                                                           |
| Hisp_Two_O | float64 | Hispanic/Latino population that identifies with 2+ races                                                                                                                                            |
| Tot_Housin | float64 | Total housing units   |
| Occup_Hous | float64  | Occupied housing units                                                                                                     |
| Vac_Housin | float64  | Vacant housing units                                                                                                       |
| GEO.id     | object   | Identifier for Census tract                                                                                                |
| pop2010    | int64    | Population of census tract in 2010                                                                                         |
| households | int64    | Number of households in Census tract                                                                                       |
| pop_16up   | int64    | Population of individuals 16+                                                                                              |
| employed   | int64    | Employed individual count                                                                                                  |
| unemployed | int64    | Unemployed individual count                                                                                                |
| geometry   | geometry | A column representing geometric or spatial data related to the Census tract,  likely used for mapping or spatial analysis. |


## LAcounty

| Column Name | DType    | Description/Comments?                                                                                                                                                                               |
|-------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| fid         | float64  | Unique identifer for each record in dataset                                                                                                                                                         |
| STATEFP10   | object   | State FIPS code                                                                                                                                                                                     |
| COUNTYFP10  | object   | County FIPS code                                                                                                                                                                                    |
| TRACTCE10   | object   | FIPS code for census tract                                                                                                                                                                          |
| GEOID10     | object   | Block identifier; a concatenation of 2010 Census state Federal Information  Processing Standards (FIPS) code, county FIPS code, census tract code,  and tabulation block number                     |
| NAME10      | object   | 2010 Census tabulation block name; a concatenation of "Block", Census state Federal Information Processing Standards (FIPS) code, county FIPS  code, census tract code, and tabulation block number |
| NAMELSAD10  | object   | Name of census tract                                                                                                                                                                                |
| MTFCC10     | object   | The MAF/TIGER Feature Class Code, indicating the type of geographic  feature represented                                                                                                            |
| FUNCSTAT10  | object   | functional status code defines the current functional status of a  geographic entity                                                                                                                |
| ALAND10     | float64  | Area of census tract that is land                                                                                                                                                                   |
| AWATER10    | float64  | Area of census tract that is water                                                                                                                                                                  |
| INTPTLAT10  | object   | latitude coordinate of the locator of the census tract                                                                                                                                              |
| INTPTLON10  | object   | longitude coordinate of the locator of the census tract                                                                                                                                             |
| STATEFP10_  | object   | State FIPS code                                                                                                                                                                                     |
| COUNTYFP10_ | object   | County FIPS code                                                                                                                                                                                    |
| GEOID10_2   | object   | Block identifier; a concatenation of 2010 Census state Federal Information  Processing Standards (FIPS) code, county FIPS code, census tract code,  and tabulation block number                     |
| NAME10_2    | object   | 2010 Census tabulation block name; a concatenation of "Block", Census state Federal Information Processing Standards (FIPS) code, county FIPS  code, census tract code, and tabulation block number |
| NAMELSAD_1  | object   | Name of census tract                                                                                                                                                                                |
| MTFCC10_2   | object   | Another version of the MAF/TIGER Feature Class Code                                                                                                                                                 |
| FUNCSTAT_1  | object   | functional status code defines the current functional status of a  geographic entity                                                                                                                |
| ALAND10_2   | float64  | Area of census tract that is land                                                                                                                                                                   |
| AWATER10_2  | float64  | Area of census tract that is water                                                                                                                                                                  |
| INTPTLAT_1  | object   | latitude coordinate of the locator of the census tract                                                                                                                                              |
| INTPTLON_1  | object   | longitude coordinate of the locator of the census tract                                                                                                                                             |
| Tot_Pop     | float64  | Total population count                                                                                                                                                                              |
| One_Race    | float64  | One race population count                                                                                                                                                                           |
| White       | float64  | White population count                                                                                                                                                                              |
| Afro_Amer   | float64  | Black population count                                                                                                                                                                              |
| Native      | float64  | Native American population count                                                                                                                                                                    |
| Asian       | float64  | Asian population count                                                                                                                                                                              |
| Pac_Isl     | float64  | Hawaiian/Pacific Islander population count                                                                                                                                                          |
| Other_Race  | float64  | Other race population count                                                                                                                                                                         |
| Two_Or_More | float64  | 2+ race population count                                                                                                                                                                            |
| Hispanic    | float64  | Hispanic/Latino population count                                                                                                                                                                    |
| Not_Hisp    | float64  | NonHispanic/Latino population count                                                                                                                                                                 |
| Hisp_One_R  | float64  | Hispanic/Latino population that identifies with one race                                                                                                                                            |
| Hisp_White  | float64  | Hispanic/Latino population that identifies as White                                                                                                                                                 |
| Hisp_Afro_  | float64  | Hispanic/Latino population that identifies as Black                                                                                                                                                 |
| Hisp_Nativ  | float64  | Hispanic/Latino population that identifies as Native American/Alaska Native                                                                                                                         |
| Hisp_Asian  | float64  | Hispanic/Latino population that identifies as Asian                                                                                                                                                 |
| Hisp_Pac_I  | float64  | Hispanic/Latino population that identifies as Hawaiian/Pacific Islander                                                                                                                             |
| Other       | float64  | Hispanic/Latino population that identifies as other races                                                                                                                                           |
| Hisp_Two_O  | float64  | Hispanic/Latino population that identifies with 2+ races                                                                                                                                            |
| Tot_Housin  | float64  | Total housing units                                                                                                                                                                                 |
| Occup_Hous  | float64  | Occupied housing units                                                                                                                                                                              |
| Vac_Housin  | float64  | Vacant housing units                                                                                                                                                                                |
| GEO.id      | int64    | Unique identifier associated with each geographic entity                                                                                                                                            |
| pop2010     | int64    | Population of census tract in 2010                                                                                                                                                                  |
| households  | int64    | Number of households                                                                                                                                                                                |
| pop_16up    | int64    | Population count of individuals aged 16+                                                                                                                                                            |
| employed    | int64    | Number of employed individuals                                                                                                                                                                      |
| unemployed  | int64    | Number of unemployed individuals                                                                                                                                                                    |
| geometry    | geometry | Spatial information representing the geometry or shape of Census tract                                                               |

## SCA Data

| Column Name | DType    | Description/Comments?                                                                                                                                                                               |
|-------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| OBJECTID    | int64    | Internal feature number                                                                                                                                                                             |
| GEOID10     | object   | Block identifier; a concatenation of 2010 Census state Federal Information  Processing Standards (FIPS) code, county FIPS code, census tract code,  and tabulation block number                     |
| COUNTYFP10  | object   | County FIPS code                                                                                                                                                                                    |
| TRACTCE10   | object   | FIPS code for census tract                                                                                                                                                                          |
| Cnty_Name   | object   | Name of county                                                                                                                                                                                      |
| City_Name   | object   | Name of city                                                                                                                                                                                        |
| ZIP         | int64    | Zip code                                                                                                                                                                                            |
| Acres       | float64  | Area in acres                                                                                                                                                                                       |
| SqMi        | float64  | Area in square miles                                                                                                                                                                                |
| Pop_16      | int64    | Population count age 16+                                                                                                                                                                            |
| Pop_Den     | int64    | Population density                                                                                                                                                                                  |
| Pop_Src     | object   | Source of population data                                                                                                                                                                           |
| Pop_10      | int64    | Population as of 2010                                                                                                                                                                               |
| White_Pct   | float64  | Percent of White                                                                                                                                                                                    |
| Black_Pct   | float64  | Percent of Black                                                                                                                                                                                    |
| Asian_Pct   | float64  | Percent of Asian                                                                                                                                                                                    |
| Latino_Pct  | float64  | Percent of Latino                                                                                                                                                                                   |
| Mltpl_Pct   | float64  | Percent of multiple races                                                                                                                                                                           |
| NatAm_Pct   | float64  | Percent of Native American                                                                                                                                                                          |
| PacIs_Pct   | float64  | Percent of Pacific Islander                                                                                                                                                                         |
| Other_Pct   | float64  | Percent of other races                                                                                                                                                                              |
| NonWhite_P  | float64  | Percent of non-white population                                                                                                                                                                     |
| Race_Src    | object   | Source of race data                                                                                                                                                                                 |
| Elders_Pct  | float64  | Percent of population 65+                                                                                                                                                                           |
| Elders_Rpt  | object   | Reporting status of the percentage of population 65+                                                                                                                                                |
| Elders_Src  | object   | Source of elderly population data                                                                                                                                                                   |
| SpksEng_Pc  | float64  | Percent of population that speaks English                                                                                                                                                           |
| SpksEng_Rp  | object   | Reporting status of percentage of population that speaks English                                                                                                                                    |
| SpksEng_Sr  | object   | Source of English-speaking population data                                                                                                                                                          |
| UnEmp_Rate  | float64  | Unemployment rate                                                                                                                                                                                   |
| Emp_15      | int64    | Number of employed individuals aged 15+                                                                                                                                                             |
| Emp_Den     | float64  | Employment density                                                                                                                                                                                  |
| Emp_Src     | object   | Source of unemployment data                                                                                                                                                                         |
| Income_Pct  | int64    | Percent of population with income data available                                                                                                                                                    |
| Income_Rpt  | object   | Reporting status of percentage of population with income data available                                                                                                                             |
| Income_Src  | object   | Source of income data                                                                                                                                                                               |
| Under19_Pc  | float64  | Percent of population under 19                                                                                                                                                                      |
| MHI2016     | float64  | Median household income in 2016                                                                                                                                                                     |
| fid         | float64  | Unique identifier for each record in dataset                                                                                                                                                        |
| STATEFP10   | object   | State FIPS code                                                                                                                                                                                     |
| COUNTYFP_1  | object   | County FIPS code                                                                                                                                                                                    |
| TRACTCE10_  | object   | FIPS code for census tract                                                                                                                                                                          |
| GEOID10_2   | object   | Block identifier; a concatenation of 2010 Census state Federal Information  Processing Standards (FIPS) code, county FIPS code, census tract code,  and tabulation block number                     |
| NAME10      | object   | 2010 Census tabulation block name; a concatenation of "Block", Census state Federal Information Processing Standards (FIPS) code, county FIPS  code, census tract code, and tabulation block number |
| NAMELSAD10  | object   | Name of census tract                                                                                                                                                                                |
| MTFCC10     | object   | The MAF/TIGER Feature Class Code, indicating the type of geographic  feature represented                                                                                                            |
| FUNCSTAT10  | object   | functional status code defines the current functional status of a  geographic entity                                                                                                                |
| ALAND10     | float64  | Area of census tract that is land                                                                                                                                                                   |
| AWATER10    | float64  | Area of census tract that is water                                                                                                                                                                  |
| INTPTLAT10  | object   | latitude coordinate of the locator of the census tract                                                                                                                                              |
| INTPTLON10  | object   | longitude coordinate of the locator of the census tract                                                                                                                                             |
| Tot_Pop     | float64  | Total population count                                                                                                                                                                              |
| One_Race    | float64  | One race population count                                                                                                                                                                           |
| White       | float64  | White population count                                                                                                                                                                              |
| Afro_Amer   | float64  | Black population count                                                                                                                                                                              |
| Native      | float64  | Native American population count                                                                                                                                                                    |
| Asian       | float64  | Asian population count                                                                                                                                                                              |
| Pac_Isl     | float64  | Hawaiian/Pacific Islander population count                                                                                                                                                          |
| Other_Race  | float64  | Other race population count                                                                                                                                                                         |
| Two_Or_Mor  | float64  | 2+ race population count                                                                                                                                                                            |
| Hispanic    | float64  | Hispanic/Latino population count                                                                                                                                                                    |
| Not_Hisp    | float64  | NonHispanic/Latino population count                                                                                                                                                                 |
| Hisp_One_R  | float64  | Hispanic/Latino population that identifies with one race                                                                                                                                            |
| Hisp_White  | float64  | Hispanic/Latino population that identifies as White                                                                                                                                                 |
| Hisp_Afro_  | float64  | Hispanic/Latino population that identifies as Black                                                                                                                                                 |
| Hisp_Nativ  | float64  | Hispanic/Latino population that identifies as Native American/Alaska Native                                                                                                                         |
| Hisp_Asian  | float64  | Hispanic/Latino population that identifies as Asian                                                                                                                                                 |
| Hisp_Pac_I  | float64  | Hispanic/Latino population that identifies as Hawaiian/Pacific Islander                                                                                                                             |
| Other       | float64  | Hispanic/Latino population that identifies as other races                                                                                                                                           |
| Hisp_Two_O  | float64  | Hispanic/Latino population that identifies with 2+ races                                                                                                                                            |
| Tot_Housin  | float64  | Total housing units                                                                                                                                                                                 |
| Occup_Hous  | float64  | Occupied housing units                                                                                                                                                                              |
| Vac_Housin  | float64  | Vacant housing units                                                                                                                                                                                |
| GEO.id      | object   | Unique identifier associated with each geographic entity                                                                                                                                            |
| pop2010     | int64    | Population of census tract in 2010                                                                                                                                                                  |
| households  | int64    | Number of households                                                                                                                                                                                |
| pop_16up    | int64    | Population count aged 16+                                                                                                                                                                           |
| employed    | int64    | Number of employed individuals                                                                                                                                                                      |
| unemployed  | int64    | Number of unemployed individuals                                                                                                                                                                    |
| geometry    | geometry | Spatial information representing the geometry or shape of Census tract                                                         |



## Diversity Data

| Column Name | DType    | Description/Comments?                                                                                                                                                                               |
|-------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| OBJECTID    | int64    | Internal feature number                                                                                                                                                                             |
| GEOID10     | object   | Block identifier; a concatenation of 2010 Census state Federal Information  Processing Standards (FIPS) code, county FIPS code, census tract code,  and tabulation block number                     |
| COUNTYFP10  | object   | County FIPS code                                                                                                                                                                                    |
| TRACTCE10   | object   | FIPS code for census tract                                                                                                                                                                          |
| Cnty_Name   | object   | Name of county                                                                                                                                                                                      |
| City_Name   | object   | Name of city                                                                                                                                                                                        |
| ZIP         | int64    | Zip code                                                                                                                                                                                            |
| Acres       | float64  | Area in acres                                                                                                                                                                                       |
| SqMi        | float64  | Area in square miles                                                                                                                                                                                |
| Pop_16      | int64    | Population count age 16+                                                                                                                                                                            |
| Pop_Den     | int64    | Population density                                                                                                                                                                                  |
| Pop_Src     | object   | Source of population data                                                                                                                                                                           |
| Pop_10      | int64    | Population as of 2010                                                                                                                                                                               |
| White_Pct   | float64  | Percent of White                                                                                                                                                                                    |
| Black_Pct   | float64  | Percent of Black                                                                                                                                                                                    |
| Asian_Pct   | float64  | Percent of Asian                                                                                                                                                                                    |
| Latino_Pct  | float64  | Percent of Latino                                                                                                                                                                                   |
| Mltpl_Pct   | float64  | Percent of multiple races                                                                                                                                                                           |
| NatAm_Pct   | float64  | Percent of Native American                                                                                                                                                                          |
| PacIs_Pct   | float64  | Percent of Pacific Islander                                                                                                                                                                         |
| Other_Pct   | float64  | Percent of other races                                                                                                                                                                              |
| NonWhite_P  | float64  | Percent of non-white population                                                                                                                                                                     |
| Race_Src    | object   | Source of race data                                                                                                                                                                                 |
| Elders_Pct  | float64  | Percent of population 65+                                                                                                                                                                           |
| Elders_Rpt  | object   | Reporting status of the percentage of population 65+                                                                                                                                                |
| Elders_Src  | object   | Source of elderly population data                                                                                                                                                                   |
| SpksEng_Pc  | float64  | Percent of population that speaks English                                                                                                                                                           |
| SpksEng_Rp  | object   | Reporting status of percentage of population that speaks English                                                                                                                                    |
| SpksEng_Sr  | object   | Source of English-speaking population data                                                                                                                                                          |
| UnEmp_Rate  | float64  | Unemployment rate                                                                                                                                                                                   |
| Emp_15      | int64    | Number of employed individuals aged 15+                                                                                                                                                             |
| Emp_Den     | float64  | Employment density                                                                                                                                                                                  |
| Emp_Src     | object   | Source of unemployment data                                                                                                                                                                         |
| Income_Pct  | int64    | Percent of population with income data available                                                                                                                                                    |
| Income_Rpt  | object   | Reporting status of percentage of population with income data available                                                                                                                             |
| Income_Src  | object   | Source of income data                                                                                                                                                                               |
| Under19_Pc  | float64  | Percent of population under 19                                                                                                                                                                      |
| MHI2016     | float64  | Median household income in 2016                                                                                                                                                                     |
| fid         | float64  | Unique identifier for each record in dataset                                                                                                                                                        |
| STATEFP10   | object   | State FIPS code                                                                                                                                                                                     |
| COUNTYFP_1  | object   | County FIPS code                                                                                                                                                                                    |
| TRACTCE10_  | object   | FIPS code for census tract                                                                                                                                                                          |
| GEOID10_2   | object   | Block identifier; a concatenation of 2010 Census state Federal Information  Processing Standards (FIPS) code, county FIPS code, census tract code,  and tabulation block number                     |
| NAME10      | object   | 2010 Census tabulation block name; a concatenation of "Block", Census state Federal Information Processing Standards (FIPS) code, county FIPS  code, census tract code, and tabulation block number |
| NAMELSAD10  | object   | Name of census tract                                                                                                                                                                                |
| MTFCC10     | object   | The MAF/TIGER Feature Class Code, indicating the type of geographic  feature represented                                                                                                            |
| FUNCSTAT10  | object   | functional status code defines the current functional status of a  geographic entity                                                                                                                |
| ALAND10     | float64  | Area of census tract that is land                                                                                                                                                                   |
| AWATER10    | float64  | Area of census tract that is water                                                                                                                                                                  |
| INTPTLAT10  | object   | latitude coordinate of the locator of the census tract                                                                                                                                              |
| INTPTLON10  | object   | longitude coordinate of the locator of the census tract                                                                                                                                             |
| Tot_Pop     | float64  | Total population count                                                                                                                                                                              |
| One_Race    | float64  | One race population count                                                                                                                                                                           |
| White       | float64  | White population count                                                                                                                                                                              |
| Afro_Amer   | float64  | Black population count                                                                                                                                                                              |
| Native      | float64  | Native American population count                                                                                                                                                                    |
| Asian       | float64  | Asian population count                                                                                                                                                                              |
| Pac_Isl     | float64  | Hawaiian/Pacific Islander population count                                                                                                                                                          |
| Other_Race  | float64  | Other race population count                                                                                                                                                                         |
| Two_Or_Mor  | float64  | 2+ race population count                                                                                                                                                                            |
| Hispanic    | float64  | Hispanic/Latino population count                                                                                                                                                                    |
| Not_Hisp    | float64  | NonHispanic/Latino population count                                                                                                                                                                 |
| Hisp_One_R  | float64  | Hispanic/Latino population that identifies with one race                                                                                                                                            |
| Hisp_White  | float64  | Hispanic/Latino population that identifies as White                                                                                                                                                 |
| Hisp_Afro_  | float64  | Hispanic/Latino population that identifies as Black                                                                                                                                                 |
| Hisp_Nativ  | float64  | Hispanic/Latino population that identifies as Native American/Alaska Native                                                                                                                         |
| Hisp_Asian  | float64  | Hispanic/Latino population that identifies as Asian                                                                                                                                                 |
| Hisp_Pac_I  | float64  | Hispanic/Latino population that identifies as Hawaiian/Pacific Islander                                                                                                                             |
| Other       | float64  | Hispanic/Latino population that identifies as other races                                                                                                                                           |
| Hisp_Two_O  | float64  | Hispanic/Latino population that identifies with 2+ races                                                                                                                                            |
| Tot_Housin  | float64  | Total housing units                                                                                                                                                                                 |
| Occup_Hous  | float64  | Occupied housing units                                                                                                                                                                              |
| Vac_Housin  | float64  | Vacant housing units                                                                                                                                                                                |
| GEO.id      | object   | Unique identifier associated with each geographic entity                                                                                                                                            |
| pop2010     | int64    | Population of census tract in 2010                                                                                                                                                                  |
| households  | int64    | Number of households                                                                                                                                                                                |
| pop_16up    | int64    | Population count aged 16+                                                                                                                                                                           |
| employed    | int64    | Number of employed individuals                                                                                                                                                                      |
| unemployed  | int64    | Number of unemployed individuals                                                                                                                                                                    |
| geometry    | geometry | Spatial information representing the geometry or shape of Census tract                                           |


