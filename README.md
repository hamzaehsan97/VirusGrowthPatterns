# COVID-19_Growth_Patterns

This repository includes a data science project to study growth patterns for COVID-19 virus.


### Prerequisites

To deploy the program on a local machine the following hardware/softwares are requires :

#### R
#### RStudio


The following libraries are required to recreate this app. You can download these libraries in Rstudio through Tools or through the command line using 'install.packages("Package Name")'

```
library(tidyverse) 
library(tidytext)
library(ggplot2)
library(rtweet)
library(gtrendsR)
library(plyr)
library(magrittr)
library(rvest)
library(shiny)
library(leaflet)
library(dplyr)
library(leaflet.extras)
```


## Knitting the report:

1) Open finalReport.rmd in RStudio
2) knit file to html.

## Results
https://hamza-ehsan.shinyapps.io/COVID-19_Growth_Patterns/ {Shiny-App}
https://hamzaehsan97.github.io/COVID-19_Growth_Patterns/

## Built With

* [R](https://www.r-project.org/) - R
* [RStudio](https://rstudio.com/) - R IDE



## Authors

* **Hamza Ehsan** 


## Data
* https://covid.ourworldindata.org/data/full_data.csv - [Our World in Data]
* https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset#time_series_covid_19_confirmed.csv - [Kaggle]

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Professor Andrew J Sage (https://github.com/andrewjsage)
* Sudalairaj Kumar (https://www.kaggle.com/sudalairajkumar)

## Screenshots

# Deaths Heat Map
![Death Heatmap Image](/images/Deaths_Heatmap.png?raw=true "Deaths Heat Map")

# Fatalaties Since Patient Zero
![Fatalies Graph Image](/images/latestScreenshot.png?raw=true "Fatalaties Since Patient Zero")

