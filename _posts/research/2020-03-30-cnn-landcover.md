---
title: "Different Spectral Domain Transformation for Land Cover Classification Using Convolutional Neural Networks with Multi-Temporal Satellite Imagery"
author: Daehyeon Han
date: 2020-03-30
categories: research
---
***published in Remote Sensing; [doi:10.3390/rs12071097](https://doi.org/10.3390/rs12071097)***

### Abstract

This study compares some different types of spectral domain transformations for convolutional neural network (CNN)-based land cover classification. A novel approach was proposed, which transforms one-dimensional (1-D) spectral vectors into two-dimensional (2-D) features: Polygon graph images (CNN-Polygon) and 2-D matrices (CNN-Matrix). The motivations of this study are that (1) the shape of the converted 2-D images is more intuitive for human eyes to interpret when compared to 1-D spectral input; and (2) CNNs are highly specialized and may be able to similarly utilize this information for land cover classification. Four seasonal Landsat 8 images over three study areas—Lake Tapps, Washington, Concord, New Hampshire, USA, and Gwangju, Korea—were used to evaluate the proposed approach for nine land cover classes compared to several other methods: Random forest (RF), support vector machine (SVM), 1-D CNN, and patch-based CNN. Oversampling and undersampling approaches were conducted to examine the effect of the sample size on the model performance. The CNN-Polygon had better performance than the other methods, with overall accuracies of about 93%–95 % for both Concord and Lake Tapps and 80%–84% for Gwangju. The CNN-Polygon particularly performed well when the training sample size was small, less than 200 per class, while the CNN-Matrix resulted in similar or higher performance as sample sizes became larger. The contributing input variables to the models were carefully analyzed through sensitivity analysis based on occlusion maps and accuracy decreases. Our result showed that a more visually intuitive representation of input features for CNN-based classification models yielded higher performance, especially when the training sample size was small. This implies that the proposed graph-based CNNs would be useful for land cover classification where reference data are limited.


![](https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/202003-landcover-method.jpg)

*The process of extracting 2-D polygon and matrix inputs. The figure shows a pixel with a location (m, n) from four dates (periods 1-4) with seven (N = 7) spectral bands. The pixel value of the first spectral band at (m, n) for the tth period is designated as pm,n,(t-1)×N+1. (a) A diagram of a polygon graph for pixels at (m, n). The vertices of the polygon are located on the polar coordinate, which have the same angular interval in the counterclockwise order along with pixel values as distances. (b) A diagram of a 2-D matrix from pixels at (m, n). The rows correspond to the four seasons and the columns represent spectral bands 1–7 in this figure.*

![](https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/202003-landcover-inputs.jpg)

*The range of the 2-D input features for nine land cover classes on (a) Lake Tapps, Washington, (b) Concord, New Hampshire, and (c) Gwangju, Korea. The first and second rows show the rate of occurrence of line and polygon graphs as density using the reference data. An area with a high occurrence rate means that the majority of graphs were plotted over the area. A rate of 1 indicates that every converted graph was plotted over an area, while a rate of 0 means no graph was plotted in that area. The third and fourth rows show the normalized mean and standard deviation of the reflectance for the 2-D matrix, respectively.*

![](https://github.com/daehyeon-han/daehyeon-han.github.io/raw/master/uploads/research/202003-landcover-sensitivity.jpg)

*Occlusion maps of 9 land cover classes at Lake Tapps from (a) CNN-Line model and (b) CNN-Polygon model. Red color indicates decreased accuracy for the occluded area, which indicates more contributing features. The grey-scale background image represents the frequency of the original dataset per class. Vertical lines (CNN-Line) and cross lines (CNN-Polygon) separate the four seasons.*
