# weather_analysis

In this project I have attempted to analyse data of various weather stations across the US.The total no. of weather stations is 8448.
To download the given data we can use the script: for i in seq 2015 2018

wget https://www1.ncdc.noaa.gov/pub/data/ghcn/daily/by_year/${i}.csv.gz

gzip -cd  i.csv.gz|grep−eTMIN−eTMAX|grepUS>i.csv.gz|grep−eTMIN−eTMAX|grepUS> {i}.csv

It can be seen as only the data corresponding to TMIN and TMAX is needed we dowload only those datasets.

for explanation of ELEMENT codes and their units as well as the M-FLAG, Q-FLAGS and S-FLAGS.

ftp://ftp.ncdc.noaa.gov/pub/data/ghcn/daily/readme.txt file
