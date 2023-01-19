### BST-270-Project

#### Individual project for BST 270 Reproducible Data Science at Harvard T.H. Chan School of Public Health in winter 2023

Author: Lauren Flynn

Contact: laurenflynn@hsph.harvard.edu

Here we will reproduce two plots from a fivethirtyeight article titled ["Dear Mona, Which State Has The Worst Drivers?"](https://fivethirtyeight.com/features/which-state-has-the-worst-drivers/). This article has a corresponding GitHub which contains the [data](https://github.com/fivethirtyeight/data/tree/master/bad-drivers). However, it does not contain the code of data wrangling or visualization generation. We will not attempt to reproduce the wrangling; however, the original data can be found at the  National Highway Traffic Safety Administration (NHTSA).

##### How to Use

To reproduce two of the graphics from the project, please run the file `/source/analysis.Rmd`. It can be knit in Rstudio to produce the html output. The data will be pulled from fivethirtyeight's data/bad-drivers GitHub as part of the script, so there is no need to download the data manually. The data, taken from file bad-drivers.csv from the repository, is accessed in raw form at https://raw.githubusercontent.com/fivethirtyeight/data/master/bad-drivers/bad-drivers.csv. 

##### Data Description

We will be utilizing the following variables:

| Variable   |      Original Source     |  Notes |
|:----------|:-------------|:------|
| State |  | 50 states and Washington D.C. |
| Number.of.drivers.involved.in.fatal.collisions.per.billion.miles |    National Highway Traffic Safety Administration, 2012  |   Using data per billion miles driven rather than total count to normalize the states  |
| Percentage.Of.Drivers.Involved.In.Fatal.Collisions.Who.Were.Speeding | National Highway Traffic Safety Administration, 2009 |    Year different than the number of collisions per billion miles |
| Percentage.Of.Drivers.Involved.In.Fatal.Collisions.Who.Were.Alcohol.Impaired   |      National Highway Traffic Safety Administration, 2012     |  |


##### Version Information 

R version 4.1.2 (2021-11-01) Bird Hippie https://cran.r-project.org/

RStudio 2022.07.1+554 "Spotted Wakerobin" Release (7872775ebddc40635780ca1ed238934c3345c5de, 2022-07-22) for macOS
Mozilla/5.0 (Macintosh; Intel Mac OS X 12_3_1) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.10 Chrome/69.0.3497.128 Safari/537.36 https://dailies.rstudio.com/version/2022.07.1+554.pro3/

R Packages:

- RCurl 1.98-1.9 https://cran.r-project.org/web/packages/RCurl/index.html

- Tidyverse 1.3.2 https://www.tidyverse.org/packages/#installation-and-use






