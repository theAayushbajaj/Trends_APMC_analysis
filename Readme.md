## Installing

Clone this project:

``git clone https://github.com/theAayushbajaj/Trends_APMC_analysis.git``

# Getting Started

This project consists of Analysis on APMC/Mandi prices analysis.
##### Aim: 
To understand trends in APMC (Agricultural produce market committee)/mandi price & quantity arrival data for different commodities in Maharashtra.

##### Objective:
> 1. Test and filter outliers.
2. Understand price fluctuations accounting the seasonal effect
3. Detect seasonality type (multiplicative or additive) for each cluster of APMC and commodities
4. De-seasonalise prices for each commodity and APMC according to the detected seasonality type
5. Compare prices in APMC/Mandi with MSP(Minimum Support Price)- raw and deseasonalised
6. Flag set of APMC/mandis and commodities with highest price fluctuation across different commodities in each relevant season, and year.

#### Data: 
https://drive.google.com/drive/u/0/folders/0B-zoMsiXW40gZlNtNnlINEszRTg

#### Variables description:


| Variable        | Description           | 
| ------------- |:-------------:| 
| msprice      | Minimum Support Price | 
| arrivals_in_qtl      | Quantity arrival in market (in quintal)      |   
| min_price | Minimum price charged per quintal      |   
| max_price |Maximum price charged per quintal      |  
| modal_price | Mode (Average) price charged per quintal      |  



## Usage

1. You can directly view from the html file
2. Upload it on Google Colab to see results of variables
3. You can use it on local machine as well


## Useful Resources :thumbsup:

> References during analysis

* [Ways to Detect and Remove the Outliers](https://towardsdatascience.com/ways-to-detect-and-remove-the-outliers-404d16608dba)
* [A Brief Overview of Outlier Detection Techniques](https://towardsdatascience.com/a-brief-overview-of-outlier-detection-techniques-1e0b2c19e561)
* [DBSCAN: What is it? When to Use it? How to use it.](https://medium.com/@elutins/dbscan-what-is-it-when-to-use-it-how-to-use-it-8bd506293818)
* [Visualizing DBSCAN Clustering](https://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)
* [Using Python and Auto ARIMA to Forecast Seasonal Time Series](https://medium.com/@josemarcialportilla/using-python-and-auto-arima-to-forecast-seasonal-time-series-90877adff03c)
* [Jeffrey Yau | Applied Time Series Econometrics in Python and R](https://www.youtube.com/watch?v=tJ-O3hk1vRw&t=176s)
