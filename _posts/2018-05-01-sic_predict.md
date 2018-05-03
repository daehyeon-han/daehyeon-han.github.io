---
title: "Estimation of Monthly Arctic Sea Ice Concentration using Random Forests"
date: 2018-05-01
categories: research, random_forest, arctic 
---
## Estimation of Monthly Arctic Sea Ice Concentration using Random Forests

*Youngjun Kim<sup>1</sup>, **Daehyeon Han<sup>1</sup>**, Sanggyun Lee<sup>1</sup>, Jungho Im<sup>1\*</sup>*

*1) Ulsan National Institute of Science and Technology (UNIST), Ulsan, Korea*

*in progress*


### Abstract
The sea ice has a significant role in the climate system such as climate changes, global warming, and energy balance issues. In addition, prediction of sea ice concentration is important for various functions including prediction and management of the polar ecosystem changes, understanding of climate changes, and financial issues regarding development of arctic shipping route. Many studies regarding estimation of sea ice concentration (SIC) have been conducted based on either numerical or statistical models. However, the models show relatively low estimation accuracy on anomalies from extreme cases. This study is to improve the estimation accuracy as well as examine relative importance among estimators using random forests. This study used monthly-mean SIC data from AVHRR (NOAA OISST ver.2), and other predictors from the European Centre for Medium-Range Weather Forecasts (ECMWF) ERA-interim re-analysis data. The spatial coverage of this study is 50° - 90° (S – N) / -180° - 180° (W - E) with 0.25*0.25 degree, and the temporal coverage is from January 1991 to December 2017 (26 years). This study used six estimators—(1) ice surface temperature (IST, 0-7cm layer, K), (2) 2-meter temperature (T2m, K), (3) sea surface temperature (SST, K), (4) downward long-wave radiation (DLR, J/m2), (5) forecast albedo (FAL, 0-1), and (6) one-month past SIC (SIC, 0-1). The random forest model show that results in R2 = 0.965 and RMSE = 4.37% for one-month prediction. The one-month past SIC was identified as the most contributing variable, followed by DLR, albedo, T2m, IST, and SST.


### current state 
Now we're building a model using CNN and comparing the results of RF and previous models*