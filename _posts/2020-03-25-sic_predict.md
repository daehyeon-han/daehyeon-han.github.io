---
title: "Prediction of monthly Arctic sea ice concentrations using satellite and reanalysis data based on convolutional neural networks"
author: Daehyeon Han
date: 2020-03-25
categories: research
---
***publised in The Cryosphere; [doi:10.5194/tc-14-1083-2020](https://doi.org/10.5194/tc-14-1083-2020)***

### Abstract
Changes in Arctic sea ice affect atmospheric circulation, ocean current, and polar ecosystems. There have been unprecedented decreases in the amount of Arctic sea ice due to global warming. In this study, a novel 1-month sea ice concentration (SIC) prediction model is proposed, with eight predictors using a deep-learning approach, convolutional neural networks (CNNs). This monthly SIC prediction model based on CNNs is shown to perform better predictions (mean absolute error – MAE – of 2.28 %, anomaly correlation coefficient – ACC – of 0.98, root-mean-square error – RMSE – of 5.76 %, normalized RMSE – nRMSE – of 16.15 %, and NSE – Nash–Sutcliffe efficiency – of 0.97) than a random-forest-based (RF-based) model (MAE of 2.45 %, ACC of 0.98, RMSE of 6.61 %, nRMSE of 18.64 %, and NSE of 0.96) and the persistence model based on the monthly trend (MAE of 4.31 %, ACC of 0.95, RMSE of 10.54 %, nRMSE of 29.17 %, and NSE of 0.89) through hindcast validations. The spatio-temporal analysis also confirmed the superiority of the CNN model. The CNN model showed good SIC prediction results in extreme cases that recorded unforeseen sea ice plummets in 2007 and 2012 with RMSEs of less than 5.0 %. This study also examined the importance of the input variables through a sensitivity analysis. In both the CNN and RF models, the variables of past SICs were identified as the most sensitive factor in predicting SICs. For both models, the SIC-related variables generally contributed more to predict SICs over ice-covered areas, while other meteorological and oceanographic variables were more sensitive to the prediction of SICs in marginal ice zones. The proposed 1-month SIC prediction model provides valuable information which can be used in various applications, such as Arctic shipping-route planning, management of the fishing industry, and long-term sea ice forecasting and dynamics.

<center><img src=https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/202003-sic-flowchart.png></center>

*Study area and research flow.*


<center><img src=https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/202003-sic-anomaly.png></center>
*The mean absolute SIC anomaly (a) and mean absolute errors between predicted SICs and the actual SICs by the persistence (b), RF (c), and CNN (d) during 2000–2017. As in (a–d) but for the melting (June–September) and freezing (December–March) seasons, shown in (e–f) and (i–l), respectively.*

<center><img src=https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/202003-sic-sie.png></center>
*The predicted SIEs using the anomaly persistence (a), RF (b), and CNN (c) for September 2017. Distribution of SIO values for September 2017 SIEs reported in August 2017 (d).*
