Readme file with a description of each indicator that is calculated

Each file is structured as:
[Indicator name]_[period]_[climate scenario]_[uncertainty range]_[resolution in meter].png

################################
## General indicators
################################

- T2M_daily_mean_max: 
	Title: Average daily maximum temperature
	Description: Average daily maximum temperature over the fully considered time frame

- T2M_daily_mean_max_topography: 
	Title: Daytime Urban Heat Island
	Description: Daytime Urban Heat Island, calculated as the average difference in daily maximum temperatures between each pixel and a rural pixel outside of the city. It captures the difference in temperatures due to human activities and the modification of land surfaces. A correction for topographic differences between pixels is considered by applying the lapse rate.

- T2M_daily_mean_min: 
	Title: Average daily minimum temperature
	Description: Average daily minimum temperature over the fully considered time frame

- T2M_daily_mean_min_topography: 
	Title: Nighttime Urban Heat Island
	Description: Nighttime Urban Heat Island, calculated as the average difference in daily minimum temperatures between each pixel and a rural pixel outside of the city. It captures the difference in temperatures due to human activities and the modification of land surfaces. A correction for topographic differences between pixels is considered by applying the lapse rate.

- T2M_mean: 
	Title: Average daily temperature
	Description: Average daily temperature over all time steps in the considered time frame

- MTWM:
	Title: Maximum temperature of the warmest month
	Description: The average maximum monthly temperature of the warmest month throughout the year (Bioclimatic indicator 5). Based on O'Donnel and Ignizio (2012): Bioclimatic Predictors for Supporting Ecological Applications in the Conterminous United States

- MTCM:
	Title: Minimum temperature of the coolest month
	Description: The average minimum monthly temperature of the coolest month throughout the year (Bioclimatic indicator 6). Based on O'Donnel and Ignizio (2012): Bioclimatic Predictors for Supporting Ecological Applications in the Conterminous United States

################################
## Energy indicators
################################

- Cooling degree hours: 
	Title: Annual average number of cooling degree hours
	Description: Cooling degree hours is an international standard to estimate energy usage for cooling dwellings using air conditioning (American Society of Heating Refrigerating and Air Conditioning Engineers, 2021). It is calculated as the number of hours during which the temperatures rises over 25°C, multiplied by the number of degrees the temperature rises above 25°C. The yearly average value is shown.

################################
## Health indicators
################################

- Heatwave days: 
	Title: Number of heatwave days per year
	Description: A heatwave is defined as a minimum of three days in which both the daytime and nighttime temperature exceed the 90th percentile threshold of a base period (taken as the period 2011-2020). The indicator is depicted as the average number of heatwave days per year.

- HWMI: 
	Title: Heat-wave magnitude index daily (HWMId)
	Description: The Heat-wave magnitude index daily (HMWId) is defined as the maximum magnitude of the heatwaves in a year. A detailed description can be found in Russo et al. (2015): doi:10.1088/1748-9326/10/12/124003.
 
- T2M_dayover25: 
	Title: Annual number of days Tmax > 25 °C
	Description: Annual number of days in which the maximum temperature exceeds 25 °C

- T2M_dayover30: 
	Title: Annual number of days Tmax > 30 °C
	Description: Annual number of days in which the maximum temperature exceeds 30 °C

- T2M_dayover35: 
	Title: Annual number of days Tmax > 35 °C
	Description: Annual number of days in which the maximum temperature exceeds 35 °C

- T2M_nightover20: 
	Title: Annual number of nights Tmin > 20 °C
	Description: Annual number of nights in which the minimum temperature does not drop below 20 °C. This limit is considered a 'tropical night' by several European meteorological services.
 
- T2M_nightover25: 
	Title: Annual number of nights Tmin > 25 °C
	Description: Annual number of nights in which the minimum temperature does not drop below 25 °C. This limit is considered a 'tropical night' by several South-European meteorological services.
 
- T2M_nightover28: 
	Title: Annual number of nights Tmin > 28 °C
	Description: Annual number of nights in which the minimum temperature does not drop below 28 °C. This limit is considered a 'tropical night' by several South-East Asian meteorological services.

- WBGT_dayover25: 
	Title: Annual number of days WBGT > 25 °C
	Description: Annual number of days in which the Wet Bulb Globe Temperatures (WBGT) exceeds 25 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 25 °C is considered a limit for moderate average heat stress exposure and limits highest physical outdoor activities to avoid health risk exposure.

- WBGT_dayover28: 
	Title: Annual number of days WBGT > 28 °C
	Description: Annual number of days in which the Wet Bulb Globe Temperatures (WBGT) exceeds 28 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 28 °C is considered a limit for strong average heat stress exposure and limits physical outdoor activities to avoid health risk exposure.

- WBGT_dayover295:
	Title: Annual number of days WBGT > 29.5 °C
	Description: Annual number of days in which the Wet Bulb Globe Temperatures (WBGT) exceeds 29.5 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 29.5 °C is considered a limit for very strong average heat stress exposure and limits most physical outdoor activities to a minimum to avoid health risk exposure.

- WBGT_dayover31: 
	Title: Annual number of days WBGT > 31 °C
	Description: Annual number of days in which the Wet Bulb Globe Temperatures (WBGT) exceeds 31 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 31 °C is considered a limit for extreme average heat stress exposure and limits all outdoor activities to a minimum to avoid health risk exposure.

- WBGT_hourover25:
	Title: Annual number of hours WBGT > 25 °C
	Description: Annual number of hours in which the Wet Bulb Globe Temperatures (WBGT) exceeds 25 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 25 °C is considered a limit for moderate average heat stress exposure and limits highest physical outdoor activities to avoid health risk exposure.

- WBGT_hourover28: 
	Title: Annual number of hours WBGT > 28 °C
	Description: Annual number of hours in which the Wet Bulb Globe Temperatures (WBGT) exceeds 28 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 28 °C is considered a limit for strong average heat stress exposure and limits physical outdoor activities to avoid health risk exposure.

- WBGT_hourover295:
	Title: Annual number of hours WBGT > 29.5 °C
	Description: Annual number of hours in which the Wet Bulb Globe Temperatures (WBGT) exceeds 29.5 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 29.5 °C is considered a limit for very strong average heat stress exposure and limits most physical outdoor activities to a minimum to avoid health risk exposure.
 
- WBGT_hourover31: 
	Title: Annual number of hours WBGT > 31 °C
	Description: Annual number of hours in which the Wet Bulb Globe Temperatures (WBGT) exceeds 31 °C. The WBGT provides an estimate of heat stress exposure for humans and is calculated following ISO 7243 norms. 31 °C is considered a limit for extreme average heat stress exposure and limits all outdoor activities to a minimum to avoid health risk exposure.

