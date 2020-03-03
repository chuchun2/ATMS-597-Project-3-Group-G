# ATMS-597-Project-3-Group-G
Project 3 for ATMS 597 SP 2020.


## Description 
The objective of this project is to detect the global circulation and teleconnection associated with the extreme daily precipitation at Kinshasa, Congo. We used GPCP daily precipitation over the period 1996-2019 and determined the 95th percentile of daily precipitation at Kinshasa during the months October to December. After getting the extreme precipitation (exceed 95th percentile) days, we used NCEP reanalysis data to compute the extreme precipitation day anomalies based on the long term mean (1981-2010). The following note summaries what we did in this project:

- Calculate and plot: cumulative distribution function and the 95th percentile
- Calculate and plot the long term mean, extreme precipitation day composite and anomalies for following variables: 250 hPa (wind vectors and wind speed), 500 hPa (wind vectors and geopotential height), 850 hPa (temperature, specific humidity and winds), skin temperature, surface wind, total atmospheric column water vapor, omega, and precipitation rate


## Usage

**project3_getdates.py**
- this script is used to get GPCP precipitation data and combine the data
- **combined.nc**: the combined GPCP precipitation data, saved in the following link (~2GB, too large for GitHub)
https://drive.google.com/open?id=1BnlcVUi2-u8dJ2Si00WmAAISR5oziqJi
- **datesexceeded.nc**: the extreme precipitation dates which exceed the 95th percentile, saved in the project repository

**project3_anomalies.py**
- this script is used to calculate and plot the mean fields and anomaly fields
- when calculate the extreme precipitation composite, users could choose to save the composite data instead of regenerating it in the future


## Authors and acknowledgment
Group G: Chu-Chun Chen, Kevin Gray, Lina Rivelli Zea


## License
This project is licensed under the MIT License.
