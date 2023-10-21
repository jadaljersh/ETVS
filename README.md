# ETVS
# Extreme Temperature Vulnerability Score (ETVS) by Census Tract
This web map was designed using QGIS and exported using the qgis2web plugin. The data source is the U.S. Census Tract. The Extreme Temperature Vulnerability Score (ETVS) was generated ﻿with the aid of the Entropy Weight Method (EWM). In a multi-criteria decision-making analysis, EWM was utilized to generate weights determined by the EWM, which determines the importance of the different criteria utilized for this analysis. The criteria were obtained from the 2016-2020 5-year estimates of the American Community Survey, and were non-subjectively weighed by EWM weighted sums of their respective normalization direction as follows:

Percentage of Mobile Homes - 48.4% (Maximization)

Percentage of Households With No Vehicles - 26.4% (Maximization)

Percentage of the Population Below 150% of the Poverty Line - 9.4% (Maximization)

Percentage of the Population Population Under 5 Years of Age - 6.2% (Maximization)

Percentage of the Population Above 65 Years of Age - 5.6% (Maximization)

Median Year of Structure Build - 3.9% (Minimization)

The weighted sum was created using the weights above for the normalized data fields, generating the Extreme Temperature Vulnerability Score displayed on this web map.
