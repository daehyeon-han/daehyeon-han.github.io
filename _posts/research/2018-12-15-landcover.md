---
title: "Convolutional Neural Network-Based Land Cover Classification Using 2-D Spectral Reflectance Curve Graphs With Multitemporal Satellite Imagery"
author: Daehyeon Han
date: 2018-12-15
categories: research, RS
---
***published in IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing [doi:10.1109/JSTARS.2018.2880783](http://dx.doi.org/10.1109/JSTARS.2018.2880783)***

### Abstract

Researchers constantly seek more efficient detection techniques to better utilize enhanced image resolution in accurately detecting and monitoring land cover. Recently, convolutional neural networks (CNNs) have shown high performances comparable to or even better than widely used and adopted machine learning techniques. The aim of this study is to investigate the application of CNNs for land cover classification by using two-dimensional (2-D) spectral curve graphs from multispectral satellite images. The land cover classification was conducted in Concord, New Hampshire, USA, and South Korea by using multispectral images acquired from 30-m Landsat-8 and 500-m Geostationary Ocean Color Imager images. For the construction of input data specific to CNNs, two seasons (winter and summer) of multispectral bands were transformed into 2-D spectral curve graphs for each class. Land cover classification results of CNNs were compared with the results of support vector machines (SVMs) and random forest (RFs). The CNNs model showed higher performance than RFs and SVMs in both study sites. The examination of land cover classification maps demonstrates a good agreement with reference maps, Google Earth images, and existing global scale land cover map, especially for croplands. Using the spectral curve graph could incorporate the phenological cycles on classifying the land cover types. This study shows that the use of a new transformation of spectral bands into a 2-D form for application in CNNs can improve land cover classification performance.

![](https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/201812-landcover-method.png)

*Illustration of the conversion of multispectral satellite data into a spectral curve graph. Input satellite images (left) are Landsat-8 images with 7 bands for the Concord site or GOCI images with 8 bands for South Korea site. Generated spectral curve graphs (right) are constructed by reflectance values of all bands by reference pixel in both winter and summer season for each land cover class. It should be noted that the spectral curves between two seasons were intentionally connected for better performance.*

![](https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/201812-landcover-cnn.png)

*Structure of the CNNs used in this study for land cover classification.*

![](https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/201812-landcover-mapping.png)

*Model comparisons of land cover classification results using Landsat- 8 images on 18th June, 2016, and 18th November, 2016, for the three models [upper in (a) and (b)] for two subregions in the Concord site with time series images of Google Earth available near the corresponding date [bottom in (a) and (b)].*