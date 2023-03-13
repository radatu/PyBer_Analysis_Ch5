# Pyber_Analysis_Ch5

DU-VIRT-DATA-PT-10-2022-U-B-MW—Module 5 Challenge—Pyber Analysis—Python 3.9.13, MatPlotLib

# PyBer Ride-Sharing Data Analysis

## Overview

The purpose of this analysis is to provide insights and recommendations to address disparities in ride-sharing data among the different city types: rural, suburban, and urban. We will be analyzing the ride-sharing data collected from January to April 2019, and presenting our findings to the CEO.

## Results

### Ride-sharing Data Overview

We first looked at the summary data for the three city types, which can be seen in Table 1. We found that:

1. Urban cities have the highest number of rides, drivers, and total fares.
2. Rural cities have the lowest number of rides and drivers, but have the highest average fare per ride and per driver.
3. Suburban cities fall in between urban and rural cities in terms of all metrics.

### Table 1: Summary Data by City Type

#### City Type Total Rides Total Drivers Total Fares Average Fare per Ride Average Fare per Driver

Rural 125 537 $4,327.93 $34.62 $8.06
Suburban 625 8,570 $19,356.33 $30.97 $2.26
Urban 1,625 59,602 $39,854.38 $24.53 $0.67

### Table 2: Weekly Fares by City Type

#### , Rural | Suburban | Urban

#### |:date

2019-01-06, 187.92 | 721.60 | 1661.68
2019-01-13, 67.65 | 1105.13 | 2050.43
2019-01-20, 306.00 | 1218.20 | 1939.02
2019-01-27, 179.69 1203.28 2129.51
2019-02-03, 333.08 1042.79 2086.94
2019-02-10, 115.80 974.34 2162.64
2019-02-17, 95.82 1045.50 2235.07
2019-02-24, 419.06 1412.74 2466.29
2019-03-03, 175.14 858.46 2218.20
2019-03-10, 303.94 925.27 2470.93
2019-03-17, 163.39 906.20 2044.42
2019-03-24, 189.76 1122.20 2368.37
2019-03-31, 199.42 1045.06 1942.77
2019-04-07, 501.24 1010.73 2356.70
2019-04-14, 269.79 784.82 2390.72
2019-04-21, 214.14 1149.27 2303.80
2019-04-28, 191.85 1169.04 1909.51

We then plotted the weekly fares by city type from Table 2 using a multiple-line chart, which can be seen in Figure 1.

![Figure 1: Weekly Fares by City Type](file:///Users/radatus/Desktop/GitHub/PyBer_Analysis_Ch5/analysis/PyBer_Fare_Summary.png)

We found that:

Urban cities have the highest total fares consistently over the period of analysis.
Suburban cities have fairly consistent fares, peaking in late February.
Rural cities have the lowest total fares and have more variability in fare amounts.

## Summary

Based on our analysis, we recommend the following business strategies to address disparities among the city types:

1. Increase driver incentives in rural and suburban areas to attract more drivers, which will lead to a decrease in the average fare per ride and per driver.
2. Implement surge pricing during peak hours in urban areas to increase total fares and reduce wait times for customers.
3. Expand marketing efforts in rural areas to increase awareness and demand for ride-sharing services.

By implementing these strategies, PyBer can increase its presence and market share in all city types, leading to increased revenue and profitability.
