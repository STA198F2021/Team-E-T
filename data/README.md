# data

`STAT 198 Food Security Dataset` added to `data` folder.

## STAT 198 Food Security Dataset Provenance

Our data directly related to food insecurity and employment, as well as employment, in 2019 (pre-COVID-19) and 2021 (post-COVID-19) was sourced from Feeding America, the United States’ largest hunger relief organization, that compiles national, state, and local data on food insecurity as a part of the organization’s “Map the Meal Gap” and “Coronavirus and Food Security” Research Initiatives. Our data related to education level and urbanization in North Carolinian counties was sourced from the USDA’s Economic Research Service and the results of the American Community Survey from 2015 to 2019. The results for these variables for each of the 100 North Carolinian counties were combined into one Excel sheet manually corresponding to each North Carolinian county and programmed for use in R.

Feeding America Data was sourced from here: https://www.feedingamerica.org/research/map-the-meal-gap/by-county
USDA Economic Research Service Data was sourced from here: https://www.ers.usda.gov/data-products/county-level-data-sets/download-data/

## STAT 198 Food Security Dataset Codebook

|variable                                         |description|
|:----------------                                |:----------|
|County                                           | North Carolina County each row refers to, character vector|
|2019 FI Percent                                  |Percent of County Residents Identified as Food Insecure in 2019, real number continuous variable|
|2019 Child FI Percent                            |Percent of County Residents under 18 years old Identified as Food Insecure in 2019, real number continuous variable|
|2021 FI Percentage                               |Percent of County Residents Identified as Food Insecure in 2021, real number continuous variable|
|2019-2021 FI Percent Change                      |Change in Percent of County Residents Identified as Food Insecure from 2019 to 2021, integer variable|
|2019-2021 Unemployment Change                    |Change in Percent of County Residents Identified as Unemployed from 2019 to 2021, real number continuous variable|
|2021 Child FI Percent                            |Percent of County Residents under 18 years old Identified as Food Insecure in 2021, real number continuous variable|
|2019-2021 Child FI Percent Change                |Change in Percent of County Residents under 18 years old Identified as Food Insecure from 2019 to 2021, real number variable|
|2019 Cost per Meal                               |Estimated Cost per County of the Cost of a Meal from 2019 to 2021, real number continuous variable|
|2013 Rural-urban Continuum Code                  |2013 Country Designation of Degree of Urbanization and Adjacency to a Metro Area, numerical categorical variable|
|2013 Urban Influence Code                        |2013 Country Designation of Size of Largest City/Town and Adjacency to a Metro Area, numerical categorical variable|
|Less than HS Diploma, 2015-9, Percent            |2015-9 Estimate of County Residents with Less than a High School Diploma in Education, real number continuous variable|
|Only HS Diploma, 2015-9, Percent                 |2015-9 Estimate of County Residents with only a High School Diploma in Education, real number continuous variable|
|Some College Education Completed, 2015-9, Percent|2015-9 Estimate of County Residents with Some College Education Completed, real number continuous variable|
|College Degree Obtained, 2015-9, Percent         |2015-9 Estimate of County Residents with an Associates, Bachelor's, or other Degree Obtained, real number continuous variable|