# Meteorology-Weather-Reporting--Data-Analysis
Data Analysis Comparing the Accuracy of Weather Reports by TV Networks &amp; Meteorology Sources



In this project, we will collect data on weather forecasts of U.S. TV Networks' weather forecasts. Using Python, we will analyze the 1) accuracy of these weather forecasts by comparing trhe forecasts with actual historical temperature data. 2) Secondly, we will compare the accuracy of each TV Networks with each other and with public sector weather reports and other online weather reporting organizations.

For better context, according to an article on the U.S. National Oceanic and Atmospheric Administration (NOAA) website, 5-day forecasts tend to have an accuracy of about 90%,., while 7-day foprecasts have about an 80% accuracy, and 10-day forecvasts have a much lower accuracy of only 50%. See article here: [NOAA article on weather report accuracy](https://scijinks.gov/forecast-reliability/#:~:text=A%20seven%2Dday%20forecast%20can,right%20about%20half%20the%20time.)

Based on this article, I will focus on 5-day as wel;l as 7-day forecast data.

See To-Dos section below for details on the next steps for this project as well as the methodology and metrics we will use (NB: this is still in the very early stages of this project; it's mostly a project proposal for the moment).

## To-Dos:

1) Collect various 5-day as well as 7-day U.S. weather reports data by TV Networks and other weather reporting organizations. Collect weather reports at the city level. Our main metric of interest will be the forecasted highs & lows for the day. Precipitation data would be interesting to collect as well, but might over-complicate the analysis for now. Exclude 10-day forecasts since these are a) fairly uncommon on TV broadcasts & b) likely to be very inaccurate and unreliable.

2) Collect historical temperature data. This will serve as the *actual* temperature data that we will compare with the weather reports' forecasts.

3) In relation to points 1 & 2, we will possibly need to use the Wayback Machine. 

But the challenge will be how to programmatically access the Wayback Machine for each desired day of data? Perhaps we can develop a webcrawler via Python that will iterate through various dates for the data we want to collect?

