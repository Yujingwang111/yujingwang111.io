# Crime Analysis in Washington DC | PPOL_670 Final Project

# Peace Corp

Group member: Jiawei Sun, Rongrong Sun, Yiwen Wang, Yujing Wang

## Description 
See the [project website](https://yujingwang111.github.io/yujingwang.io/) for the full analysis.
Combined with the data sources, we analyzed the crime data in Washington D.C. from 2017 to 2021, and predicted the crime data in 2022. We use `ggplot2`  to visualize the types of crime and the relationship between crime and time, and made a geospatial analysis of the crimes in the past five years. Then, we generated two machine learning models, time series and decision tree to predict crime. Besides, we also tried other models, although we failed, we still kept model records and codes.

## Problem definition
The lockdown and quarantine measures issued worldwide in response to the COVID-19 global pandemic have brought a series of impacts on daily life. Unfortunately, most of the effects of COVID-19 and the resulting lockdown have been shockingly negative - rising deaths, unemployment and the imminent global financial crisis are the most frequently reported problems around the world. 

While COVID-19 has brought about many negative effects, it has also brought about some positive changes. For example, crime rates have decreased. From 1.10% (3.1 million) in 2019 to 0.93% (2.6 million) in 2020, the percentage of people aged 12 and older who are victims of violent crime has decreased by 15%. In addition, property crime declines from 7.37% (9.8 million) of households in 2016 to 6.19% (7.9 million) of households in 2020 (Morgan & Thompson, 2022).

This has aroused our interest in crime research. In addition, from February to April 2022, there were several armed robberies in Georgetown community. Therefore, we want to analyze the crimes in the District of Columbia where we study and live in the past five years from 2017 to 2021.

## Data Source
* For this analysis, we combined multiple sources provided by the government of Washington, D.C. The [opendata.dc](https://opendata.dc.gov/search?collection=Dataset&q=crime%20incidents) is the main data source we used. This data website contains the summary of annual DC crime data. We extracted the crime data from 2017 to 2021 and made visual analysis.
* In order to better combine the crime with DC in geographical space, we find the [topographic map of DC](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-state-district-of-columbia-current-census-tract-state-based), the [metro line distribution map of DC](https://opendata.dc.gov/datasets/DCGIS::metro-lines/about), the [University distribution map of DC](https://opendata.dc.gov/datasets/DCGIS::universities-and-colleges/explore?location=38.891128%2C-77.020974%2C11.86) and [police station in DC](https://opendata.dc.gov/datasets/police-stations/explore?location=38.890899%2C-77.026467%2C12.54) respectively.

## Data extraction
For this project, we use crime data for the city of Washington DC, which are available from 2017 onwards on the city’s open data portal. Crime data for city of Washington DC available from their open data portal at: https://opendata.dc.gov. To make analysis manageable, we utilized the data from 2017-2021. We downloaded the DC crime data for 5 years,  put them into a folder called “data”.

Because we focus on property crime, after reading the data, we cleaned up the data. We split the time, month and year of the crime according to the original data. It not only lays the foundation for the following visualization, but also facilitates our prediction models.

## Detail Results
For the full detail and result, please click [here](https://yujingwang111.github.io/PPOL670_Final/)

## Authors

Contributors names and contact info

* Jiawei Sun js4880@georgetown.edu
* Rongrong Sun rs2157@georgetown.edu
* Yiwen Wang   yw826@georgetown.edu
* Yujing Wang yw790@georgetown.edu

## Reference

Dr. Qiusheng Wu, S., 2022. Using R for Crime Analysis. [online] Wetlands.io. Available at: <https://wetlands.io/maps/Crime-Analysis-Using-R.html#enhance_data_layer> [Accessed 2 May 2022].

Morgan, R. and Thompson, A., 2022. Criminal Victimization, 2020. [online] Bureau of Justice Statistics. Available at: <https://bjs.ojp.gov/library/publications/criminal-victimization-2020> [Accessed 2 May 2022].

Otexts.com. 2022. Chapter 3 Time series decomposition Forecasting: Principles and Practice (3rd ed). [online] Available at: <https://otexts.com/fpp3/decomposition.html> [Accessed 4 May 2022].

Rpubs.com. 2022. RPubs - Chicago Crime: A Time Series Analysis. [online] Available at: <https://rpubs.com/Arifyunan360/Chicago_Crime> [Accessed 5 May 2022].
